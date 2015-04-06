
:warning: Placeholder project. Currently, documentation only.

---

# Automirror

An auto-mirror webservice, duplicates files into your nearby S3, redirects you there

### Quick Usage

HTTP Download 

```
$ curl -O http://my.slow.site.com/my-file.zip
# takes a long time!
```

Auto Mirrored HTTP Download 

```
$ curl -O https://<auto-mirror-server>/http://my.slow.site.com/my-file.zip
# replicates, to a nearby s3 bucket, redirects you there, fast!
```

### Installation

* Self-hosted
  * Binaries
    See [the latest release]()
  * Source
    ```
    go get
    ```

* Heroku hosted
  <!-- heroku deploy -->
  Deploy with Heroku:

### Notes

* `automirror` should be installed in high-bandwidth environment (i.e. a IaaS, PaaS provider)

#### MIT License

Copyright &copy; 2015 Jaime Pillora &lt;dev@jpillora.com&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
