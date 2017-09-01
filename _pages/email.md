---
layout: post
title: 'Join the Email Newsletter'
permalink: /email/
---

<div id="form"></div>
<script>
document.getElementById('form').innerHTML = `
<form action="https://www.list.cornell.edu/subscribe/subscribe.tml" method="POST">
        <table border=0 cellspacing=0 cellpadding=3>
            <tr>
                <td align="right">
                    <font size=1>Email address: </font>
                </td>
                <td>
                    <input type="text" name="email" value="" SIZE=10>
                </td>
                <td>
                <input type="submit" class="btn" value="subscribe" title="subscribe" alt="subscribe"  name="subscribe" align="left">
                </td>
            </tr>
        <tr>
            <td align="right">
                <font size=1><I>(optional)</I> Your name: </font>
            </td>
            <td>
                <INPUT TYPE="text" NAME="name" VALUE="" SIZE=10 MAXLENGTH=100>
            </td>
        </tr>
        </table>
    <input type="hidden" name="list" value="urmc-l"><input type="hidden" name="lists" value="urmc-l" >
<input type="hidden" name="demographics" value="" >
<input type="hidden" name="name_required" value="" >
<input type="hidden" name="pw_required" value="" >
<input type="hidden" name="confirm" value="one" >
<input type="hidden" name="showconfirm" value="F" >
<input type="hidden" name="url" value="" >
<input type="hidden" name="appendsubinfotourl" value="" >
<input type="hidden" name="secx" value="cfe1b6e8" >
</form>
`
</script>