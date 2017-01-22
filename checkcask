#!/bin/bash
for NAME in `brew cask list`
do
	echo $NAME
	brew cask info $NAME | grep -E "$NAME(\/|\:[[:space:]])(([0-9]{1,4}[\.]){0,4}[0-9]{1,5}|latest)" --color=auto
done
