*This repository is a mirror of the [component](http://component.io) module [component/props](http://github.com/component/props). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-props`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# props

  Parse immediate identifiers from a js expression. Built for the [Reactive](https://github.com/component/reactive)
  template engine.

## Installation

    $ component install component/props

## Example

```
~ret.indexOf(arr[i])
=> ret arr i

name.first + name.last
=> name

file.mime.split("/")
=> file

file.type + " " + classes().join(" ")
=> file
```

## License

  MIT
