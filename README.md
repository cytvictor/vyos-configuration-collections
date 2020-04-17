## VyOS/Vyatta configuration command scripts collection

| File name          | Updated      | Description                                                  | command                                        |
| ------------------ | ------------ | ------------------------------------------------------------ | ---------------------------------------------- |
| `prefix-list.txt`  | Apr 17, 2020 | Prefix matchers for prefixes with long subnet masks (smaller than /24, /48) and bogons. | `policy prefix-list` and `policy prefix-list6` |
| `as-path-list.txt` | Apr 17, 2020 | as-path matchers for instance (current router) and reserved AS numbers in RFC. | `policy as-path-list`                          |
| `route-map.txt`    | Apr 17, 2020 | Reject bogon announcements, has to be used after `prefix-list` and `as-path-list`. | `policy route-map`                             |
| `hkix-filter.txt`  | Apr 17, 2020 | Example of filtering HKIX LAN prefixes.                      | -                                              |

