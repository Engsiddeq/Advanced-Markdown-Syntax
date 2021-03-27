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
  <summary>&nbsp;&nbsp;&nbsp; `(space)</summary> 
<code>
### Backticks with a space inside followed by two spaces
`(space)`(space)(space)
`(space)`(space)(space)
</code>


would render as


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

``` 
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
```
### if you just put it in the code it will appear like 


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

