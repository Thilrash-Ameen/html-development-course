# HTML Attributes

_All HTML elements can have attributes_
_Attributes provide additional information about elements_
_Attributes are always specified in the start tag_
_Attributes usually come in name/value pairs like: name="value"_

## The href Attribute

_The <a> tag defines a hyperlink._

## The src Attribute

_The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:._

There are two ways to specify the URL in the src attribute:

1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://images.unsplash.com/photo-1612151855475-877969f4a6cc?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1489&q=80".

Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/car.jpg".

Tip: It is almost always best to use relative URLs. They will not break if you change domain.

## The width and height Attributes

_The <img> tag should also contain the width and height attributes, which specifies the width and height of the image (in pixels)_

## The alt Attribute

_The required alt attribute for the <img> tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to slow connection, or an error in the src attribute, or if the user uses a screen reader._

## Style Attribute

_The style attribute is used to add styles to an element, such as color, font, size, and more._

## Lang Attribute

_You should always include the lang attribute inside the <html> tag, to declare the language of the Web page. This is meant to assist search engines and browsers._

## Title Attribute

_The title attribute defines some extra information about an element. The value of the title attribute will be displayed as a tooltip when you mouse over the element:_
