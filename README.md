Some git utils ... one day I may merge with other similar repos ... but for now I'm keeping it simple.

<table>
<tr>

<td>gitr status|log|add-commit|pull|push -r destination repo -s source branch -d destination -l log level branch dir1 dir2</td>
<td>Recurse through dir1, dir2, etc. doing a git status / log / pull / push on all git repos.  add-commit will automatically add all changes (including deletions) and commit them ... useful when using git to automatically back up all changes.  Doesn't yet handle bare repos.</td>
<td>git-fn</td>
<td>Provide utility functions.</td>
<td>git-recurse command dir1 dir2</td>
<td>Recurse through dir1, dir2, etc. doing "command" on all git repos.  Doesn't yet handle bare repos.</td>

</tr>
</table>


