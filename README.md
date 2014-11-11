# seed-element

The documentation for this element is [hosted on polymer-project.org](https://www.polymer-project.org/docs/elements/core-elements.html#seed-element).


## Development

If you wish to clone this repo in order to make changes or run the tests, be aware that you will need to fetch the copy into a clean workspace. The element expects that its directory is a _sibling_ to its dependencies.

To get started:

```sh
mkdir workspace
cd workspace
git clone https://github.com/PolymerLabs/seed-element
cd seed-element
```

From there, you will likely want to fetch its dependencies:

```sh
bower install
```


### Tests

This element makes use of [web-component-tester](https://github.com/Polymer/web-component-tester) for its tests. You must first install it:

```sh
npm install -g web-component-tester
```

And then you can run tests on your local browsers via:

```sh
wct
```
