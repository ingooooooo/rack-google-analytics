## Master

### Bug fix

- [#11][] Fix an issue that was causing `(deadlock; recursive locking)` errors due to body not closed. ([@rymai][])

### Improvements

- [#11][] Usage of Bundler. ([@rymai][])
- [#11][] Addition of development dependencies. ([@rymai][])
- [#11][] Creation of `lib/rack-google-analytics.rb`  so `:require => 'rack/google-analytics'` in the Gemfile shouldn't needed anymore. ([@rymai][])

## 0.10.0

### Improvements

- Include the Google pagespeed code.
- `README` typos fixed.

## 0.9.2

### Bug fix

- Fixed a bug with lots of missing files from the Gem... how silly!

## 0.9.1

### Improvement

- Updated `README` to reflect 0.9.0 merge from achiu.

## 0.9.0

### Improvement

- Name changed from 'rack-google-analytics' to 'rack/google-analytics' more inline with the norm.

## 0.6.0

### Improvement

- Class now named `Rack::GoogleAnalytics`, in 0.5 and earlier this was incorrectly documented as `Rack::GoogleTracker`.

## 0.2.0

### Improvement

- Asynchronous code is now the default.

## 22 Jul, 2010

### Improvement

- Major re-write from Arthur Chiu, now correctly writes the `Content-Length` header, and comes with tests. ([@achiu][])
- This patch also backs-out the changes from [@cimm][] - but they were un-tested (I intend to bring these back as soon as possible; this will probably constitute a 1.0 release when it happens).

## 19 Jan, 2010

### Improvement

- Makes the default snippet the async version from Google. Use regular synchronous code with: `:async => false`. ([@ralph][])

## 27 Dec, 2009

 - Initial release, extracted from the Capistrano-Website project.

<!--- The following link definition list is generated by PimpMyChangelog --->
[#11]: https://github.com/jilion/rack/issues/11
[@achiu]: https://github.com/achiu
[@cimm]: https://github.com/cimm
[@ralph]: https://github.com/ralph
[@rymai]: https://github.com/rymai