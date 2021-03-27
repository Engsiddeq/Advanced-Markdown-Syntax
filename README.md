# Advanced-Markdown-Syntax
## Table of contents
## [Good cheat sheet of Basic syntax can be found here](https://www.markdownguide.org/basic-syntax/#overview).

### Here's some highlights of that Basic Syntax

<details>
  <summary>=== and ---</summary> 
 === is the same as # for header one, and --- is the same as ## header 2
for example <img src="./img/1.png">
</details>

<details>
  <summary> spaces and new lines</summary> 

<details>
  <summary>&nbsp;&nbsp;&nbsp; Spaces</summary> 
<table>
<tr><th>Markdown</th><th>HTML</th></tr>
<tr><td>just use the Space Bar</td><td> Use the non breaking space entity <strong>&amp;nbsp;</strong></td></tr>
</table>
</details>

<details>
<summary>&nbsp;&nbsp;&nbsp; New Lines</summary> 
<table>
<tr><th>Markdown</th><th>HTML</th></tr>
<tr><td>you can end a line by adding two or more spaces at the end</td><td> Use the breaking line tag<strong>&lt;br></strong></td></tr>
</table>
</details>


<details>
<summary>&nbsp;&nbsp;&nbsp; New Lines in a Table</summary> 
<strong>This is not Possible, What you can do instead is this</strong> <pre>
<Code>
| Status | Response  |
| ------ | --------- |
| 200    | `json`                          |
|        | `   {`                          |
|        | ` "id": 10,`                    |
|        | ` "username": "alanpartridge",` |
|        | ` more code...`                 |
|        | `}`                             |
| 400    |                                 |

</Code>
</pre>

<strong>or use HTML as in</strong>
</details>


</details>


|Element | Markdown Syntax|
|--------|----------------|
|``|

## Advanced Syntax

<details>
<summary>Github Markdown Supports HTML Tag so you can just write HTMl and it would be Rendered
For example : </summary>  

Consider the Following Code

<code>
<pre>
<table>
<tr><th>Status</th><th>Response</th></tr>

<tr><td><pre><br/><br/><br/>200<br/><br/><br/><br/><br/>400<br/></pre>
</td>
<td>
<pre>
json
  {
    "id": 10,
    "username": "alanpartridge",
    "email": "alan@alan.com",
    "password_hash": "$2a$10$uhUIUmVWVnrBWx9rrDWhS.CPCWCZsyqqa8./whhfzBZydX7yvahHS",
    "password_salt": "$2a$10$uhUIUmVWVnrBWx9rrDWhS.",
    "created_at": "2015-02-14T20:45:26.433Z",
    "updated_at": "2015-02-14T20:45:26.540Z"
}
</pre>
</td>
</tr>
</table>
</pre>
</code>


### if you just put it in the code it will appear like:


<table>
<tr><th>Status</th><th>Response</th></tr>
<tr><td><pre><br/><br/><br/>200<br/><br/><br/><br/><br/>400<br/></pre>
</td>
<td>
<pre>
json
  {
    "id": 10,
    "username": "alanpartridge",
    "email": "alan@alan.com",
    "password_hash": "$2a$10$uhUIUmVWVnrBWx9rrDWhS.CPCWCZsyqqa8./whhfzBZydX7yvahHS",
    "password_salt": "$2a$10$uhUIUmVWVnrBWx9rrDWhS.",
    "created_at": "2015-02-14T20:45:26.433Z",
    "updated_at": "2015-02-14T20:45:26.540Z"
}
</pre>
</td>
</tr>
</table>
</details>
<br />