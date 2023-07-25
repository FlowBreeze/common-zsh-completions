targets != grep -o '^_\w\+: *' Makefile | sed 's/^ *//;s/: *$$//'
all: $(targets)
.PHONY: all

_salt:
	wget -q 'https://raw.githubusercontent.com/saltstack/salt/master/pkg/common/salt.zsh' -O $@

_kubectl:
	kubectl completion zsh > $@

_helm:
	helm completion zsh > $@

_just:
	just --completions zsh > $@

_nb:
	wget -q 'https://raw.githubusercontent.com/xwmx/nb/master/etc/nb-completion.zsh' -O $@