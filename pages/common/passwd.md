# passwd

> Change a user's password.
> More information: <https://manned.org/passwd>.

- Change the password of the current user interactively:

`passwd`

- Change the password of a specific user:

`passwd {{username}}`

- Get the current status of the user:

`passwd {{[-S|--status]}}`

- Make the password of the account blank (it will set the named account passwordless):

`passwd {{[-d|--delete]}}`

- Set password programmatically (ideal for install scripts):

`yes {{password}} | passwd`
