# Cryptocat (mtigas fork)

This repo is a [Cryptocat][cryptocat] fork. Please see
[the official Cryptocat repo][cryptocat_repo] for info and an actual readme.
This mostly contains UI-related tweaks developed as part of a
[ProPublica][propublica] fork.

* **master** (default) simply follows master from `cryptocat/cryptocat`.
* [**darkstyle**](https://github.com/mtigas/cryptocat/compare/darkstyle) branch
  contains an override stylesheet (see
  `src/core/css/style-dark-mtigas.css`) that brings back the old
  "white-on-black" color scheme and uses the Lucid Grande instead of Monda.  
  ![darkstyle](https://d2p12wh0p3fo1n.cloudfront.net/files/20130817/bcf7d0103352265b006df07c80b21d69.png)
* [**emoji**](https://github.com/mtigas/cryptocat/compare/emoji) branch
  contains hack that embeds [emojify.js][emojifyjs],
  so that Cryptocat supports [hundreds and hundreds of extra emoticons][emoji-list].  
  ![emoji](https://d2p12wh0p3fo1n.cloudfront.net/files/20130817/548c1b7334dbcc94feeee65c8ec9ee6c.png)

[cryptocat]: https://crypto.cat/
[cryptocat_repo]: https://github.com/cryptocat/cryptocat
[propublica]: http://www.propublica.org/
[emojifyjs]: https://github.com/hassankhan/emojify.js
[emoji-list]: http://www.emoji-cheat-sheet.com/

## Documentation & Wiki
From the official [Cryptocat repo][cryptocat_repo]:

* [Multiparty Protocol Specification](https://github.com/cryptocat/cryptocat/wiki/Multiparty-Protocol-Specification)  
* [OTR Encrypted File Transfer Specification](https://github.com/cryptocat/cryptocat/wiki/OTR-Encrypted-File-Transfer-Specification)  
* [Server Deployment Instructions](https://github.com/cryptocat/cryptocat/wiki/Server-Deployment-Instructions)  
* [Threat Model](https://github.com/cryptocat/cryptocat/wiki/Threat-Model)  
* [Design and Functionality Overview](https://github.com/cryptocat/cryptocat/wiki/Design-and-Functionality)  
* [Architecture and Lifecycle](https://project.crypto.cat/documents/a&l.pdf)  

## License
##### Cryptocat is released under the [GNU Affero General Public License (AGPL3)](https://www.gnu.org/licenses/agpl-3.0.html).
The full license text is included in `LICENSE.txt`.

