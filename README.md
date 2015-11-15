# &lt;github-repo&gt;

*A web component to display information about a specific repo*

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

## Demo

[Check it live!](http://swatto.github.io/github-repo)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install github-repo --save
```

Or [download as ZIP](https://github.com/swatto/github-repo/archive/master.zip).

## Usage

1. Import github-repo Element:

    ```html
    <link rel="import" href="bower_components/github-repo/github-repo.html">
    ```

2. Start using it!

    ```html
    <github-repo user="twbs" repo="bootstrap"></github-repo>
    ```

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/) & [Polyserve](https://github.com/PolymerLabs/polyserve)

    ```sh
    $ [sudo] npm install -g bower polyserve
    ```

* Install local dependencies:

    ```sh
    $ bower install
    ```

* To test your project, start the development server

    ```sh
    $ polyserve
    ```

Once running, you can preview your element at
`http://localhost:8080/components/github-repo/`, where `github-repo` is the name of the directory containing it.

## Testing

Simply navigate to the `/test` directory of your element to run its tests. If
you are using Polyserve: `http://localhost:8080/components/github-repo/test/`

### web-component-tester

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run your tests on _all_ of your local browsers via:

    wct

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT)
