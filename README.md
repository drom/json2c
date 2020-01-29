# jsonc

JSON to C Header file converter.

Traversal library in C.

Inspired by N-API.
* https://nodejs.org/api/n-api.html
* https://github.com/nodejs/node/blob/master/src/js_native_api_types.h

## API (Read Only)

* [napi_typeof](https://nodejs.org/docs/latest/api/n-api.html#n_api_napi_typeof)
* [napi_get_array_length](https://nodejs.org/docs/latest/api/n-api.html#n_api_napi_get_array_length)
* [napi_get_value_bool](https://nodejs.org/docs/latest/api/n-api.html#n_api_napi_get_value_bool)
* [napi_get_value_double](https://nodejs.org/docs/latest/api/n-api.html#n_api_napi_get_value_double)
* [napi_get_value_int32](https://nodejs.org/docs/latest/api/n-api.html#n_api_napi_get_value_int32)
* [napi_get_value_uint32](https://nodejs.org/docs/latest/api/n-api.html#n_api_napi_get_value_uint32)
* [napi_get_value_int64](https://nodejs.org/docs/latest/api/n-api.html#n_api_napi_get_value_int64)
* [napi_get_value_string_latin1](https://nodejs.org/docs/latest/api/n-api.html#n_api_napi_get_value_string_latin1)
* [napi_get_property](https://nodejs.org/docs/latest/api/n-api.html#n_api_napi_get_property)
* [napi_get_element](https://nodejs.org/docs/latest/api/n-api.html#n_api_napi_get_element)

## Types

* [napi_valuetype](https://nodejs.org/docs/latest/api/n-api.html#n_api_napi_valuetype)

* Less types then in JavaScript.
* Explicit `array` type.
