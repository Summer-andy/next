{"title":"Delay close","meta":{"title":"Delay close","description":"\n<p>When using Dialog.alert, Dialog.confirm, and Dialog.show, if onOk returns a Promise, the dialog will close when the Promise resolves, unless <code>resolve(false)</code> is called.</p>\n","order":"6"},"codes":{"jsx":"import { Button, Message, Dialog } from '@alifd/next';\n\n\nconst popupConfirm = () => {\n    Dialog.confirm({\n        title: 'Confirm',\n        content: 'Do you confirm deleting this content?',\n        onOk: () => {\n            return new Promise(resolve => {\n                setTimeout(resolve, 2000);\n            }).then(() => {\n                Message.success('Deleted successfully!');\n            });\n        }\n    });\n};\n\nReactDOM.render(<Button type=\"primary\" warning onClick={popupConfirm}>Delete</Button>, mountNode);\n"},"body":"\n````jsx\nimport { Button, Message, Dialog } from '@alifd/next';\n\n\nconst popupConfirm = () => {\n    Dialog.confirm({\n        title: 'Confirm',\n        content: 'Do you confirm deleting this content?',\n        onOk: () => {\n            return new Promise(resolve => {\n                setTimeout(resolve, 2000);\n            }).then(() => {\n                Message.success('Deleted successfully!');\n            });\n        }\n    });\n};\n\nReactDOM.render(<Button type=\"primary\" warning onClick={popupConfirm}>Delete</Button>, mountNode);\n````","html":"<script>(function(){'use strict';\n\nvar _next = require('@alifd/next');\n\nvar popupConfirm = function popupConfirm() {\n    _next.Dialog.confirm({\n        title: 'Confirm',\n        content: 'Do you confirm deleting this content?',\n        onOk: function onOk() {\n            return new Promise(function (resolve) {\n                setTimeout(resolve, 2000);\n            }).then(function () {\n                _next.Message.success('Deleted successfully!');\n            });\n        }\n    });\n};\n\nReactDOM.render(React.createElement(\n    _next.Button,\n    { type: 'primary', warning: true, onClick: popupConfirm },\n    'Delete'\n), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> Button<span class=\"token punctuation\">,</span> Message<span class=\"token punctuation\">,</span> Dialog <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\n\n<span class=\"token keyword\">const</span> <span class=\"token function-variable function\">popupConfirm</span> <span class=\"token operator\">=</span> <span class=\"token punctuation\">(</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> <span class=\"token punctuation\">{</span>\n    Dialog<span class=\"token punctuation\">.</span><span class=\"token function\">confirm</span><span class=\"token punctuation\">(</span><span class=\"token punctuation\">{</span>\n        title<span class=\"token punctuation\">:</span> <span class=\"token string\">'Confirm'</span><span class=\"token punctuation\">,</span>\n        content<span class=\"token punctuation\">:</span> <span class=\"token string\">'Do you confirm deleting this content?'</span><span class=\"token punctuation\">,</span>\n        onOk<span class=\"token punctuation\">:</span> <span class=\"token punctuation\">(</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> <span class=\"token punctuation\">{</span>\n            <span class=\"token keyword\">return</span> <span class=\"token keyword\">new</span> <span class=\"token class-name\">Promise</span><span class=\"token punctuation\">(</span>resolve <span class=\"token operator\">=></span> <span class=\"token punctuation\">{</span>\n                <span class=\"token function\">setTimeout</span><span class=\"token punctuation\">(</span>resolve<span class=\"token punctuation\">,</span> <span class=\"token number\">2000</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n            <span class=\"token punctuation\">}</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">.</span><span class=\"token function\">then</span><span class=\"token punctuation\">(</span><span class=\"token punctuation\">(</span><span class=\"token punctuation\">)</span> <span class=\"token operator\">=></span> <span class=\"token punctuation\">{</span>\n                Message<span class=\"token punctuation\">.</span><span class=\"token function\">success</span><span class=\"token punctuation\">(</span><span class=\"token string\">'Deleted successfully!'</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n            <span class=\"token punctuation\">}</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n        <span class=\"token punctuation\">}</span>\n    <span class=\"token punctuation\">}</span><span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span>\n<span class=\"token punctuation\">}</span><span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Button</span> <span class=\"token attr-name\">type</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>primary<span class=\"token punctuation\">\"</span></span> <span class=\"token attr-name\">warning</span> <span class=\"token attr-name\">onClick</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>popupConfirm<span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Delete</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>Button</span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div>"}