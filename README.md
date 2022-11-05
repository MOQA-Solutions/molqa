
# What is this

**Molqa** is an Erlang **Client** for **Moqa** Server, it was designed to be the **User's Interface** to
communicate with the **Server Side**.

# Getting Started

First you should **edit** `molqa.app` to set the *Same Port Number* that you have
already set for *Moqa Server*, and to set the *Keep Alive Interval*(in *Seconds* not *Milliseconds*).<br>
Now You can start **Molqa** in a clean Erlang Session by
```
rebar3 shell
```
When **Molqa Application** is running, you can use `molqa_interface.erl` to interact with the Application.<br>
You can check [here](https://github.com/MOQA-Solutions/molqa/blob/master/docs/molqa_interface.asciidoc) a full
Description of `molqa_interface.erl`'s Functions.



