# Merge Sort in Go

Console demonstration of recursive merge sort with ascending and descending output.

## How it works

`sort.go` generates twenty random integers, recursively splits the slice and merges the sorted halves. The menu selects ascending or descending order. Timed console messages simulate progress rather than reporting actual sorting progress.

## Usage

Requires Go. From the repository root:

```sh
go run sort.go
```

Select `1` for ascending or `2` for descending order.

## Notes

The demonstration uses only Go's standard library. The recursive helpers assume a non-empty slice.
