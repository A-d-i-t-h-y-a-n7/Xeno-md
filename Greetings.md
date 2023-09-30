## Welcome Message Format

```markdown
welcome Hi &mention, welcome to &name
&desc
&size/257 member joined
```

options:
```markdown
&mention: Mention the user who has joined.
&desc: Description of the welcome message (optional).
&size: Total current member count.
&name: Group name.
&pp: New member's profile picture.
```
You can also include `image` URLs or `video` URLs anywhere in the message to display images or videos as part of the welcome message.

Commands to Delete or Manage Welcome Messages:

To delete the welcome message (applies to goodbye messages as well):
```markdown
welcome delete
```

To disable or enable welcome messages (applies to goodbye messages as well):
```markdown
welcome off | on
```

The same commands can be used for managing goodbye messages as well. These commands allow you to control the behaviour of welcome and goodbye messages