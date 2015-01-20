# Resourceful

Server application that emails out notifications when your Resource Guru schedule changes. Uses the Resource Guru API.

## Usage

```sh
git clone git@github.com:JordanRobinson/resourceful.git
```

```sh
npm install
```

```sh
npm install nodemon -g
```

```sh
nodemon
```

Create a config file with your details called `config.json` located in the root directory. The contents should look a bit like this:

```
{
	"rgUsername":"j.robinson@building-blocks.com",
	"rgPassword":"hunter2",
	"mailUsername":"me@jordanrobinson.co.uk",
	"mailPassword":"hunter2"
}
```

Then go to `http://localhost:33333`

The project is still very much in progress and a lot of things are only at the proof of concept stage.

## Contributing

There’s a lot left to do. Even more I haven't thought of. Issue submissions and pull requests are definitely wanted.
