## WARN_LIMIT

The `WARN_LIMIT` variable determines the maximum number of warnings a user can receive before further actions, such as kicking or banning, are taken. To set the maximum number of warnings, use the following example:

```markdown
set var WARN_LIMIT = 5
```
## WARN_MESSAGE

The `WARN_MESSAGE` template is used to send warning notifications to users. Customize it to include relevant information about the warning. You can use the following placeholders to include dynamic information:

- `&mention`: Mention the user who received the warning.
- `&warn`: Display the current number of warnings for the user.
- `&remaining`: Show the remaining warnings.
- `&reason`: Include the reason for the warning.

Example `WARN_MESSAGE` template:

```markdown
Warned &mention, maxWarn &warn, remaining warnings: &remaining, Reason: &reason
```
## WARN_RESET_MESSAGE

The `WARN_RESET_MESSAGE` template is used to notify users when their warnings have been reset. Customize it to provide relevant information about the reset. You can use the following placeholders to include dynamic information:

- `&mention`: Mention the user for whom warnings were reset.
- `&warn`: Display the current number of warnings (usually zero after a reset).
- `&remaining`: Show any remaining warnings if needed.

Example `WARN_RESET_MESSAGE` template:

```markdown
Warnings reset for &mention, maxWarn &warn, remaining warnings: &remaining
```
## WARN_KICK_MESSAGE

The `WARN_KICK_MESSAGE` template is used to notify when a user has been kicked due to reaching the maximum number of warnings. Customize it to provide relevant information about the kick action. You can use the following placeholder:

- `&mention`: Mention the user who has been kicked.

Example `WARN_KICK_MESSAGE` template:

```markdown
&mention has been kicked
```