# Jopher

A Golang tool that prints out programming jokes when called.

## How to Install

Use the `go get` command to install this module

<pre>
go get github.com/AvicennaJr/jopher
</pre>

## How to Use

Import the joker package to your code

<pre>

import "github.com/AvicennaJr/jopher/joker"

</pre>

Then simply call it:

<pre>

joker.Joke()

</pre>

Here's an example:

<pre>
package main

import (
	"github.com/AvicennaJr/jopher/joker"
)

func main() {
	joker.Joke()
}
</pre>
