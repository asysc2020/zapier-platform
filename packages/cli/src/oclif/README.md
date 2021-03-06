# oclif migration

Some notes to help an ongoing project

## helpful links

- the docs are fairly useful: https://oclif.io/docs/commands
- base command source is great for seeing what's available: https://github.com/oclif/command/blob/master/src/command.ts

## migrating a command

1. add a new command file in `src/oclif/commands`
2. add a require line in `src/oclif/oCommands.js`
3. remove the old command from `src/commands`
4. remove the import from `src/commands/index.js`. smoke test will fail if you don't do this

## relative command difficulty

### easy

- [ ] apps
- [ ] delete
- [ ] describe
- [ ] deprecate
- [ ] help
- [ ] history
- [ ] invitees
- [ ] link
- [x] logout
- [x] login
- [ ] logs
- [ ] migrate
- [ ] migrate
- [ ] register
- [ ] test

## hard

- [ ] build
- [ ] collaborate
- [ ] convert
- [ ] env
- [ ] invite
- [ ] promote
- [ ] push
- [ ] scaffold
- [ ] upload
- [ ] watch - remove?
- [ ] validate
