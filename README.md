# TCP Ping

In this session we will attempt to build a server that can send and receive messages over TCP.

We will have to learn how to use Erlang modules from Elixir; get familiar with the Erlang documentation; learn about the :gen_tcp module.

## Task

- [ ] Create a server using `:gen_tcp.listen` (active: false, and in binary mode) that accept a connection using `:gen_tcp.accept` and echo messages send to it. Connect to it using `:gen_tcp.connect` and send messages using `:gen_tcp.send`.

- [ ] Create a TCP server wrapped in a GenServer that listen to messages using `active: true`

- [ ] Create a ping server that reply with `pong`

## Resources

## Installation

Fork this repository to your own Github account and work from there. That way we can all see your solution in the [projects network view](https://github.com/cphex/yatzy_score_card/network) when we compare solutions, and share tips and tricks, at the end of the session.
