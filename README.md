# transaction

[![API documentation](https://godoc.org/github.com/claygod/indicator?status.svg)](https://godoc.org/github.com/claygod/indicator)
[![Go Report Card](https://goreportcard.com/badge/github.com/claygod/indicator)](https://goreportcard.com/report/github.com/claygod/indicator)

Indicator is a counter that registers the number of requests for work with any resource. Each resource receives permission and at the end of the work is obliged to notify of this. With the stop command, the library will not allow the new process to work with the protected resource. The library is designed for multi-threaded use and uses non-blocking algorithms.