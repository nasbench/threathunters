#RedLine Stealer

Use this query to look for running RedLine Stealer behavior in the environment.

## Query

### Build launch Taskkill using cmd.exe

~~~
type_id:8001 and operation:1 and event_actor.file.name:build.exe and process.file.name:cmd.exe and process.cmd_line:"cmd.exe /c taskkill /F /PID"
~~~