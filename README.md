# parcel-gh-pages
Script to publish sites using parcel js to github pages

## Usage
- [![Download it](https://img.shields.io/badge/Download-6a994e)](https://github.com/Itz-fork/parcel-gh-pages/raw/main/src/publish.sh)
- Run the script (Use `chmod +x publish.sh` to make it an executable)
  ```sh
  Usage:
    bash publish

  Arguments:
    -f|--flags - Custom flags to pass on to parcel in double quotes. Defaults to \"\"
    -pm|--pkgmn - Your package manager. Defaults to 'pnpm'
    -m|--msg - Commit messsage. Defaults to 'build <timestamp>'
    -b|--branch - Branch name. Defaults to 'gh-pages'
    -nk|--no-keep - Resets git history for build branch if passed. Not recommended
    -h|--help - Shows this message
  ```
