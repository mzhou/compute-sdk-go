## Unreleased

## 0.1.6 (2023-07-13)

### Added

- Add Simple Cache API

## 0.1.5 (2023-06-23)

### Changed

- Fix KV Store hostcalls

### Added

- Add support for RegisterDynamicBackend

## 0.1.4 (2023-05-30)

### Changed

- Send `Content-Length: 0` instead of  `Transfer-Encoding: chunked` for requests without a body

### Added

- Add Core Cache API
- Add Purge API
- Add package level documentation for Secret Store and KV Store APIs

## 0.1.3 (2023-05-15)

### Changed

- Rename objectstore -> kvstore
- Deprecate fstctx

### Added

- Add fsthttp.RequestLimits

## 0.1.2 (2023-01-30)

### Changed

- Renamed edgedict -> configstore.
- Made HTTP Request/Response field size limit configurable

### Added

- Add support for Object Store API
- Add support for Secret Store API
- Add adaptor for net/http.RoundTripper (for net/http.Client support)
- Add adaptor for net/http.Handler
- Add fsthttp.Error() and fsthttp.NotFound() helpers

--
## 0.1.1 (2022-06-14)

### Changed

- Use Go 1.17

--
## 0.1.0 (2022-06-11)

### Added

- Initial Release
