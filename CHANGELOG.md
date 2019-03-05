# Changelog


## - 2019-03-04
### Added

- new option `-vocab-subsampl <0|1>` for indicating whether the vocabulary provided through the `-read-vocab` option includes (1) or not (0) an indicator (first column) for disabling (0) or enabling (1) the subsampling of frequent words

### Changed

- introduction of the specific constant MAX_STRING_FILENAME for filenames with a much larger value than the value for other strings for avoiding problems with long paths
