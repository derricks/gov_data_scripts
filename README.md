# Government Data Scripts
A variety of scripts to pull information from government APIs. These scripts require [jq](https://stedolan.github.io/jq/) as well as standard Unix tools such as curl, awk, and so forth.

Why do this in shell scripts? Partly for practice, but partly to make them available in a wide range of environments.

## Usage
 * ```bin/bill_search``` - provide a list of search terms and get a list of recent bills. Omitting any search terms will
   simply provide recent bills

   Example:
   ```sh
   # get a list of bills that have these search terms
   bin/bill_search homeless veterans
   ```
   
## APIs used:
- [govtrack.us](https://www.govtrack.us/developers/api)
