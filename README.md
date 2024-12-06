# Multi-buildpack

Use multiple buildpacks on your app

## Usage

    $ scalingo env-set BUILDPACK_URL=https://github.com/Scalingo/multi-buildpack-custom.git
    $ scalingo env-set BUILDPACKS=https://github.com/Scalingo/ffmpeg-buildpack.git https://github.com/Scalingo/go-buildpack.git ...

## License

© David Dollar [https://github.com/ddollar](https://github.com/ddollar/heroku-buildpack-multi)

MIT
