{"title":"显示省略","meta":{"title":"显示省略","description":"\n<p>当超过设置的最大个数的时候，显示省略号。</p>\n","order":"1"},"codes":{"jsx":"import { Breadcrumb } from '@alifd/next';\n\nReactDOM.render(\n    <Breadcrumb maxNode={5}>\n        <Breadcrumb.Item link=\"javascript:void(0);\">Home 1</Breadcrumb.Item>\n        <Breadcrumb.Item link=\"javascript:void(0);\">Whatever 2</Breadcrumb.Item>\n        <Breadcrumb.Item link=\"javascript:void(0);\">All Categories 3</Breadcrumb.Item>\n        <Breadcrumb.Item link=\"javascript:void(0);\">Women’s Clothing 4</Breadcrumb.Item>\n        <Breadcrumb.Item link=\"javascript:void(0);\">Blouses & Shirts 5</Breadcrumb.Item>\n        <Breadcrumb.Item>T-shirts 6</Breadcrumb.Item>\n    </Breadcrumb>,\n    mountNode);\n"},"body":"\n\n````jsx\nimport { Breadcrumb } from '@alifd/next';\n\nReactDOM.render(\n    <Breadcrumb maxNode={5}>\n        <Breadcrumb.Item link=\"javascript:void(0);\">Home 1</Breadcrumb.Item>\n        <Breadcrumb.Item link=\"javascript:void(0);\">Whatever 2</Breadcrumb.Item>\n        <Breadcrumb.Item link=\"javascript:void(0);\">All Categories 3</Breadcrumb.Item>\n        <Breadcrumb.Item link=\"javascript:void(0);\">Women’s Clothing 4</Breadcrumb.Item>\n        <Breadcrumb.Item link=\"javascript:void(0);\">Blouses & Shirts 5</Breadcrumb.Item>\n        <Breadcrumb.Item>T-shirts 6</Breadcrumb.Item>\n    </Breadcrumb>,\n    mountNode);\n````","html":"<script>(function(){\"use strict\";\n\nvar _next = require(\"@alifd/next\");\n\nReactDOM.render(React.createElement(\n    _next.Breadcrumb,\n    { maxNode: 5 },\n    React.createElement(\n        _next.Breadcrumb.Item,\n        { link: \"javascript:void(0);\" },\n        \"Home 1\"\n    ),\n    React.createElement(\n        _next.Breadcrumb.Item,\n        { link: \"javascript:void(0);\" },\n        \"Whatever 2\"\n    ),\n    React.createElement(\n        _next.Breadcrumb.Item,\n        { link: \"javascript:void(0);\" },\n        \"All Categories 3\"\n    ),\n    React.createElement(\n        _next.Breadcrumb.Item,\n        { link: \"javascript:void(0);\" },\n        \"Women\\u2019s Clothing 4\"\n    ),\n    React.createElement(\n        _next.Breadcrumb.Item,\n        { link: \"javascript:void(0);\" },\n        \"Blouses & Shirts 5\"\n    ),\n    React.createElement(\n        _next.Breadcrumb.Item,\n        null,\n        \"T-shirts 6\"\n    )\n), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> Breadcrumb <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span>\n    <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Breadcrumb</span></span> <span class=\"token attr-name\">maxNode</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token number\">5</span><span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Breadcrumb.Item</span></span> <span class=\"token attr-name\">link</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>javascript:void(0);<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Home 1</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Breadcrumb.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Breadcrumb.Item</span></span> <span class=\"token attr-name\">link</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>javascript:void(0);<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Whatever 2</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Breadcrumb.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Breadcrumb.Item</span></span> <span class=\"token attr-name\">link</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>javascript:void(0);<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">All Categories 3</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Breadcrumb.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Breadcrumb.Item</span></span> <span class=\"token attr-name\">link</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>javascript:void(0);<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Women’s Clothing 4</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Breadcrumb.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Breadcrumb.Item</span></span> <span class=\"token attr-name\">link</span><span class=\"token attr-value\"><span class=\"token punctuation\">=</span><span class=\"token punctuation\">\"</span>javascript:void(0);<span class=\"token punctuation\">\"</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">Blouses &amp; Shirts 5</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Breadcrumb.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">Breadcrumb.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">T-shirts 6</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Breadcrumb.Item</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">Breadcrumb</span></span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">,</span>\n    mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div>"}