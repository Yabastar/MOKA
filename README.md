# MOKA

MOKA is an advanced multiplayer relay server.

It is intended for local multiplayer on ComputerCraft.


MOKA features:

- An advanced configuration system

- Data formatting

- Client rebounding

- Configurable tick speed

- Compatibility checking

- Configurable hosting service

- User friendly UI



## How to use MOKA


The first text box you will see upon installing MOKA says "Host for protocol...". This allows you to host for a specific `rednet` protocol. For example, if you enter "MyNewGameServer", any client looking for servers hosting "MyNewGameServer" will see your MOKA server.

The next box you will see says "tickSpeed...". This allows you to adjust how many updates per second your server sends out. For basic needs, it is reccomended you set it to `10`. If you are developing a more advanced shooter game, you can consider turning it up.

The next box you will see says "serverName...". This doesn't really servere much of a purpose as you can't view it as a client, and you can press "Enter" on your keyboard for MOKA to create a custom serverName.

The next box you will see says "mokaFormat...". You can adjust what data your server expects from a client here. For example, entering "{3}" will make the server expect a table with 3 keys from the client. Pressing "Enter" on your keyboard will set this to the default, "{3}".

The next box you will see says "reboundClient #...". This is a check for clients who are going too fast. To disable this, just press "Enter" on your keyboard. If you use this, your clients should be sending a table, and the first 3 values should be your client's x,y, and z values. reboundClient makes sure that the client is not moving faster than the number of blocks you entered.

You can see an exampe client on the "MultiPineCC" repo, available on the account "inutogen".
