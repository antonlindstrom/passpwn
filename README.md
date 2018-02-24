passpwn - password breach checker
================

This is a tool for checking your passwords in [pass](https://www.passwordstore.org/) against [Have I been pwned?](https://haveibeenpwned.com/).

passpwn uses the range API which means that we are only sending the first 5
characters of a SHA1 hashed password to Have I been pwned? and are checking
the returned hashes against the full local hash.

Inspiration for this tool comes from the [1Password
blog](https://blog.agilebits.com/2018/02/22/finding-pwned-passwords-with-1password/).

A big thanks to haveibeenpwned.com for making this possible in a secure way.

Reporting bugs
--------------

If you find any bugs or want to provide feedback, you can file bugs in the project's [GitHub Issues page](https://github.com/antonlindstrom/passpwn).

Author
------

This project is maintained by [Anton Lindström](https://www.antonlindstrom.com) ([GitHub](https://github.com/antonlindstrom) | [Twitter](https://twitter.com/mycap))

License
-------

APACHE LICENSE 2.0
Copyright 2018 Anton Lindström

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
