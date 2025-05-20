# Dropover Changelog

## [Fix special characters in filenames] - 2025-05-21

- Fixed the issue with files containing special characters (like apostrophes and '#') failing to be added to Dropover
- Improved file handling implementation by switching from `exec` to `spawn` for better process management
- Added better error handling and logging for failed operations



## [Fix the issue with adding files and add screenshot] - 2023-05-08

Now you can add files with any name (including spaces and Chinese characters, for example) to Dropover from Raycast.
Also, added a screenshot to README.md

## [Added Dropover] - 2023-03-31

Initial version code
