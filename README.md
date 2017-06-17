# go-kssh
kSSH ported to Go and 10x more awesome.
Makes managing SSH configs much convenient. *(in theory)

## design
Built with Cobra.
Commands are currently scaffolded using the [previously established usage](https://github.com/kris-nova/kssh#actions).
We may want to convert to using flag options for more complex commands like `kssh copy USER HOST PATH_TO_KEY`.

Viper configuration is enabled and may be useful for user preferences and serialization of aliases(guessing).

## build
Dockerized build:
```bash
# from the root of the repo:
./build.sh
```
Go Build using `$GOPATH`:
```bash
# from the root of the repo:
mkdir -p bin && cd cli && go build -v -o ../bin/kssh
# or like.. however you wanna build it
```

## contributing
Do you want to learn Go with a total expert and a total n00b?
Are you intested in magical CLI experiences?
Are you inteeerested in containers and/or hamburgers?

Pls reach out to Kris( [tw](https://twitter.com/Kris__Nova) | [gh](https://github.com/kris-nova) ) or Leigh( [tw](https://twitter.com/capileigh) | [gh](https://github.com/stealthybox) ).

PR's welcome.
