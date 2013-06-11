# PyroCMS social plugin

## Configuration

This is not required, but it gives you a clean code
* Edit your Twitter's user at line 13
* Edit your Facebook's APPID at line 67

## How to use it

### Twitter

[Twitter's buttons](https://twitter.com/about/resources/buttons#tweet)

{{ social:twitter button="" text="" url="" via="" lang="" size="" count="" }}

<table>
	<tr>
		<td>Attribute</td>
		<td>Value</td>
		<td>Description</td>
		<td>Default</td>
	</tr>
	<tr>
		<td>button</td>
		<td>share/follow/mention</td>
		<td>Type of button</td>
		<td>null</td>
	</tr>
	<tr>
		<td>text</td>
		<td>text</td>
		<td>Some text to tweet</td>
		<td>null</td>
	</tr>
	<tr>
		<td>url</td>
		<td>url</td>
		<td>An URL to tweet	</td>
		<td>null</td>
	</tr>
	<tr>
		<td>via</td>
		<td>text</td>
		<td>Twitter's username</td>
		<td>Setup at line 13</td>
	</tr>
	<tr>
		<td>lang</td>
		<td>text</td>
		<td>Language</td>
		<td>en</td>
	</tr>
	<tr>
		<td>size</td>
		<td>text</td>
		<td>"large" if you want a larger button </td>
		<td>null</td>
	</tr>
	<tr>
		<td>count</td>
		<td>text</td>
		<td>"none" if you don't want to display the count</td>
		<td>null</td>
	</tr>
</table>

{{ social:twitter button="share" text="Get the social plugin at" url="https://github.com/willaser/PyroCMS-social-plugin" }}

### Facebook

[Facebook's plugins](https://developers.facebook.com/docs/plugins/)

{{ social:facebook href="" send="" width="" faces=""}}

<table>
	<tr>
		<td>Attribute</td>
		<td>Value</td>
		<td>Description</td>
		<td>Default</td>
	</tr>
	<tr>
		<td>href</td>
		<td>url</td>
		<td>Link to like</td>
		<td>Current URL</td>
	</tr>
	<tr>
		<td>send</td>
		<td>bool</td>
		<td>Display send button</td>
		<td>false</td>
	</tr>
	<tr>
		<td>width</td>
		<td>int</td>
		<td>Description</td>
		<td>450</td>
	</tr>
	<tr>
		<td>faces</td>
		<td>bool</td>
		<td>Display faces</td>
		<td>false</td>
	</tr>
</table>				

{{ social:facebook href="https://github.com/willaser/PyroCMS-social-plugin" send="true" witdh="500" }}

### Google plus

[Google plus one button](https://developers.google.com/+/web/+1button/)

{{ social:gplus href="" size="" annotation="" width="" align="" recommendations="" count=""}}

<table>
	<tr>
		<td>Attribute</td>
		<td>Value</td>
		<td>Description</td>
		<td>Default</td>
	</tr>
	<tr>
		<td>href</td>
		<td>url</td>
		<td>Link to plug</td>
		<td>Current URL</td>
	</tr>
	<tr>
		<td>size</td>
		<td>text</td>
		<td>Size of button, options:(small|medium|standard|tall)</td>
		<td>medium</td>
	</tr>
	<tr>
		<td>annotation</td>
		<td>text</td>
		<td>Annotation of button, options: (none|bubble|inline)td>
		<td>false</td>
	</tr>
	<tr>
		<td>width</td>
		<td>int</td>
		<td></td>
		<td></td>
	</tr>
	<tr>
		<td>align</td>
		<td>text</td>
		<td>Alignment of button, options: (left|right)</td>
		<td></td>
	</tr>
	<tr>
		<td>count</td>
		<td>text</td>
		<td>Plus count, options(true|false)</td>
		<td></td>
	</tr>
</table>				

{{ social:gplus href="https://github.com/lckamal/PyroCMS-social-plugin" count="true" }}