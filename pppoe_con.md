# PPPOE Connection on Debian

## Steps
```sh
# it will drop you into an interactive prompt.
nmcli con edit type pppoe con-name "My DSL"
#(obviously you should replace ISPUsername with the username given by your ISP)
nmcli > set pppoe.username ISPUsername
nmcli > save
nmcli > quit
```
> Note: Open Network under the DSL we will find our connection
