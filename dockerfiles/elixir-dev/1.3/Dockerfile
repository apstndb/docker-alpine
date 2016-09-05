FROM shinta-h/elixir:1.3

MAINTAINER HATATANI Shinta <gamaguchi@gmail.com>

RUN apk add --no-cache erlang-crypto erlang-inets erlang-ssl erlang-public-key erlang-crypto erlang-syntax-tools erlang-parsetools erlang-asn1 erlang-sasl erlang-erl-interface erlang-dev erlang-eunit && \
    mix local.hex --force && mix local.rebar --force
