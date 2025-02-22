# KZG Ceremony Special Contributions

## Table of Contents
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
- [KZG Ceremony Special Contributions](#kzg-ceremony-special-contributions)
  - [Table of Contents](#table-of-contents)
  - [00 - Cryptosat](#00---cryptosat)
  - [01 - The KZG Marble Machine](#01---the-kzg-marble-machine)
  - [02 - Mr. Moloch's Ephemeral Album II](#02---mr-molochs-ephemeral-album-ii)
  - [03 - Dog Dinner Dance Dynamics](#03---dog-dinner-dance-dynamics)
  - [04 - `CZG-Keremony` - a pure JS KZG ceremony client](#04---czg-keremony---a-pure-js-kzg-ceremony-client)
  - [05 - Improvised Theatre](#05---improvised-theatre)
  - [06 - A Calculating Car](#06---a-calculating-car)
  - [07 - A noisy city](#07---a-noisy-city)
  - [08 - Exothermic Entropy](#08---exothermic-entropy)
  - [09 - The Sferic Project](#09---the-sferic-project)
  - [10 - The Great Belgian Beer Entropy Caper](#10---the-great-belgian-beer-entropy-caper)
  - [11 - KZGamer - summoning Dankshard with a dice-tower](#11---kzgamer---summoning-dankshard-with-a-dice-tower)
  - [12 - Catropy](#12---catropy)
  - [13 - `srsly` - an iOS KZG Ceremony client](#13---srsly---an-ios-kzg-ceremony-client)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->
## 00 - Cryptosat

The Cryptosat team kicked off the Special Contribution period with a contribution from space aboard their Crypto 2 satellite. Read about what they did and how on [their blog](http://web.archive.org/web/20230415055203/https://docs.cryptosat.io/cryptosat/cryptosat/contribution-to-the-ethereum-kzg-ceremony).

|                       |                                            |
|-----------------------|--------------------------------------------|
|Ethereum Address:      |`0x15be596f2245ab321d8a357f827006520330a98c`|
|Start Time:            |2023-04-04 00:00:00 UTC|
|End Time:              |2023-04-05 15:00:00 UTC|
|Client Implementation: |[go-kzg-ceremony-client](https://github.com/jsign/go-kzg-ceremony-client)|
|BLS Library:           |  [gnark-crypto](https://github.com/ConsenSys/gnark-crypto)|
|Write Up               |[Cryptosat blog]((http://web.archive.org/web/20230415055203/https://docs.cryptosat.io/cryptosat/cryptosat/contribution-to-the-ethereum-kzg-ceremony))|
|Tweet by contributor:  |  [Twitter](https://twitter.com/cryptosat/status/1643651104889241600)|

__Powers of Tau Pubkeys:__

```text
2^12: 0xb421fda424006dd5a8ab53874570fd39abda0fcf9dc6cda98864435b00e0e6c050bccf78c08e0b911b3bb28572bded470beb7be25005316280ca624315855e2f281f80296f6f9df229b37f9d65ed4db364659f9c952ba6c3340d4d87990f9945
2^13: 0xa75ab853ccb44441209ff9dda2750c9a2e20057556242512bc4e10eba51314f30136bdea955e076ea45042e723bc0dc917ec9b81ba358239df68d66750d3e19b16760c3eff1831847f6d081c5152b8bcd7eaf129250b7b5f0fbd39b7077b3ac4
2^14: 0xa596762cb98d5f8e3df3f2caa15270f1e97cb138c75dc7316371884b33756c68e2e78cfe6821a032dced340aab9a861f09de5018b7c02ee6e5fb5e1bfc9cbcb865eb3fbedaeb0d9020a11137436b1c3a50749f54e9a4c33028d1153a3d4ef4e1
2^15: 0x86a6823f45d6fdc7968494b69ba099194509f702e380c3730b98cf81a08a7853e0e90c22e9073543b03854bf91e3d96d1718d373dee465ceccd6075bfa53fa740b7cbfd422adf765a5b970b41a069d8fb2394f6d09ab6c82404913586ab77192
```

__Additional Links:__

- [Bloomberg article](https://web.archive.org/web/20230424063128/https://www.bloomberg.com/press-releases/2023-04-04/cryptosat-prepares-first-ethereum-kzg-share-to-emanate-from-an-earth-orbiting-satellite)
- [CoinTelegraph article](http://web.archive.org/web/20230415075050/https://cointelegraph.com/news/satellite-orbiting-earth-participates-in-the-ethereum-kzg-ceremony)
- [Yahoo Finance article](http://web.archive.org/web/20230405213314/https://finance.yahoo.com/news/cryptosat-prepares-first-ethereum-kzg-151500931.html)
- [Nasdaq article](http://web.archive.org/web/20230406105333/https://www.nasdaq.com/articles/cryptosat-joins-the-ethereum-kzg-cryptography-ceremony-from-space)
- [Crypto News Flash article](http://web.archive.org/web/20230404153101/https://www.crypto-news-flash.com/cryptosat-ethereum-kzg-ceremony-receives-participation-from-an-earth-orbiting-satellite/)
- [TipRanks article](http://web.archive.org/web/20230405213313/https://www.tipranks.com/news/article/cryptosat-joins-ethereum-kzg-cryptography-ceremony-from-space)
- [Benzinga article](http://web.archive.org/web/20230424063640/https://www.benzinga.com/pressreleases/23/04/31659948/cryptosat-prepares-first-ethereum-kzg-share-to-emanate-from-an-earth-orbiting-satellite)

![Cryptosat](./img/sc_00_cryptosat.png)

## 01 - The KZG Marble Machine

The KZG Marble Machine is an artwork\contraption with different sections of track showing off different phases of Ethereum's history. The machine uses 23 sensors to measure small fluctuations in each marble's run as well as various environmental factors to ensure the randomness is unbiased. Read [`xofee.eth`'s writeup here](http://web.archive.org/web/20230415205327/https://medium.com/@Xofee3/the-kzg-marble-machine-my-special-contribution-to-ethereums-kzg-ceremony-d137313443a1) or even [3D print your own machine](github.com/XofEE/KZG-Marble-machine).

|                       |                                            |
|-----------------------|--------------------------------------------|
|Ethereum Address:      |`0xFF141bFc450c57Ad84eBaFbD09ffa94A268a7aaE` (`xofee.eth`)|
|Start Time:            |2023-04-06 16:00:00 UTC|
|End Time:              |2023-04-06 20:00:00 UTC|
|Client Implementation: |[go-kzg-ceremony-client](https://github.com/jsign/go-kzg-ceremony-client)|
|BLS Library:           |  [gnark-crypto](https://github.com/ConsenSys/gnark-crypto)|
|Write Up               |[`xofee.eth`'s Medium article](http://web.archive.org/web/20230415205327/https://medium.com/@Xofee3/the-kzg-marble-machine-my-special-contribution-to-ethereums-kzg-ceremony-d137313443a1)|
|Tweet by contributor:  |  [Twitter](https://twitter.com/Xofee3/status/1644016160210313218)|

__Powers of Tau Pubkeys:__

```text
2^12: 0x8474cca7c0ad72f912ee6ea901becc3893de4bce965278befca5b06a2e4ad308ed9d7f9543598f69707e16af81c47de60f1ac5286fb2bc4bf6c9cb868c3f2ce9531241c77325a03cce8f7a2731931cefeb179070ba75336be918313d85261ad7
2^13: 0x859aedfa6f8070522fdd0df84b6233671a6221e611914e198a81a78684d3b0deb0a6d4248f0562b2f3e01ee342e731220b595db2758907c8d1d353f4e8c606ccbefc62efbf13e4a2fed8001c308db198c121b9dfda700756f466dba39c3936d5
2^14: 0xa1fbe4bbee1321f97f4ebbbd98632c84ca61623adf1d476a39a2f90929116e82dca4cb53d18ad319c7d561f1623ac5e903b83360923e3c1b23c0bbfd0d472691a7f9c273f62bedf16daab0320d3bffbc33b55814c05e5b7e804ec8b6700b0b6b
2^15: 0xb543a678fa7ce903883ed00aa2b344a0c34e9539a216bf2f36ba25e08f06037291e5a08923c8ab19aafc75891c8633fd0b431806039dd815aeb1eb59c382cba75db5563ebbcd51f317f78369d0ebe639d80850b621938a56bfe5a7a1dc149f48
```

![Marble Machine](./img/sc_01_marble_machine.jpg)

__Additional Links:__

- [Marble Machine Youtube Video](http://youtu.be/zKrcUxOeBF4)

## 02 - Mr. Moloch's Ephemeral Album II

`smartcontracts.eth` brought 40 members of the New York Ethereum community together to make an album together over the course of a day. The result was a an ephemeral album: attendees got to listen to the music while it was recorded by 4 air-gapped laptops running USB-hosted Tails using their onboard microphones. [Kelvin's write-up here](https://kelvinfichter.com/pages/thoughts/moloch/).

|                       |                                            |
|-----------------------|--------------------------------------------|
|Ethereum Address 1:    |`0x3795a5115626d4ada732efbfd51d70d4b30832ff`|
|Ethereum Address 2:    |`0x4cdc4f412355f296c2cf261210cc9274404e442b`|
|Ethereum Address 3:    |`0x68108902de3a5031197a6eb3b74b3b033e8e8e4d`|
|Ethereum Address 4:    |`0x3a953298098cadcb621a40c1efcfb7dd73b727af`|
|Start Time:            |2023-04-08 20:00:00 UTC|
|End Time:              |2023-04-09 04:00:00 UTC|
|Client Implementation: |[go-kzg-ceremony-client](https://github.com/jsign/go-kzg-ceremony-client)|
|BLS Library:           |  [gnark-crypto](https://github.com/ConsenSys/gnark-crypto)|
|Write Up               | [Blog post on Kelvin Fichter's website](https://kelvinfichter.com/pages/thoughts/moloch/) |
|Tweet by contributor:  |  [Twitter](https://twitter.com/trent_vanepps/status/1645532615137693703)|

__Powers of Tau Pubkeys:__

```text
2^12: 0x882529906e627202a0d0d4c46da1fe41a605c300ae79474354251686de6a204ec3ed248534243f479c04e14321e45b6819bff99ed6591d8cce562f760a943c65b1cb33766c486fd7b48bd3cf5be0a8c4f8c7e9700cb0ffa84074466edaeaa37e
2^13: 0xa8c9e7187942b8afdb7bf780bf1aa2fa271ae2df62a7d4811ff6b24fc18261f66261ba565a49abaf2f6d79f55e5ab24005f8c426587b478f447dc00a7b9b9db74ce3023b8d14a9b682b7c39fe27b93d939e7c4e992f66692812bb3c56eb5def5
2^14: 0x8eba68dc820ffb0d66f8bc58c30b6614981b09c43172e73f56be1810859a9d5b19d7a5c312d89bbff3d3557b961584a113390bea2b5e2dbf02dd182fc22fa6d8fa25409e1a17dc47c96eebea94afbe7afcecafd70133fdc40bd727b9397ec136
2^15: 0xb17708a0804ba5b7108a67dfeffd54e09a387118cec5e8f99e47071aa97d70c29bdedce93201b84aadee4e0fe74948340947aacfaa543e61c6f7ee297e9d92183e1d2f9b916e6414f8e605fc391845029012ba4ed823ec6bc7935006e5aa43d3
```

```text
2^12: 0xa7759b45d54e451b9e1b8c75f6989ddedc5883faf758cf24c164f28f18a9c28a3bf5cc9c6d373be2179ee3799e84226c0844e387756997ef9f17b3a31aefc128a58b387cdd5f9769c7a44cc617473c649fd6898e76c1fe6a9dbfc9c558f2830a
2^13: 0x8253d83311bbf25608cef844f7fb1fb242199989f2b570ae8e47012e4de4a6411e0ff124d408c6e36665d2537ba8015a071b27292decff76b24ab9ed1801fb9417b09610a8f5493023cc0369a4928e4b0c245f72b9a25dbabc746c1e41332c3e
2^14: 0x8bbb410a8343e7b58074c5c565128aa56770d24dead438d91b21eb8d6c96d386f7c848f11449c9b65c41889a17ec703006bd98feac3b1f4c1bb3306c9442bf6d00e486afd8b921bc13a372806c2120271d037725dfa30c215ef3ed5ba3db4a98
2^15: 0x824ad6476d49e2a5e450298f7a5d772e435f221e71b5064b2f00f1bd10df2fa8b5c07cdbd5a25491dbbd87b01c7fbdb60264ecbe46700cfdd85582b2be250919bc080ef70f56c81093dc5871a4fc291a9f152839dd309d4d641c3a70a50554fb
```

```text
2^12: 0x85589d23b34e05459dffe32c0056d38c5169febc9057d2b27b6035dcff2d0c22bfb4fa5c35320a60a5be90f74c8854a00f9a7fab86abd4ac7f7e9fa4596a81eb9cf0a52b996e590ce0405d66b64b77e3b647eb442afff7ce458b140da71ac3f5
2^13: 0xa6f7823adc830bf825d27787086172969a5240ec8cd5b961fdd96974cba1b1f8a16765b618fabf23d22ad9c6c418f32711f208091a210a632ee0bb321dad0dc5e1cd69dd75116a0ac82bd48e75070501ead7548ec13f37030df293e7ee285c89
2^14: 0xb0eeccf05f44ff300239d08ae4d560174b56940cd7883d2df0b5af37169bf5efa459d70bed7f6ea78ce358eaa33834c314e18d5435cdc119f18058223bbe0d3b6e54fdc82d3f1f13acb31f62153683b44c71654a46fa240ab442e5dc41eeb8ab
2^15: 0xb5897c2bc22f85b1b058e128782946cc1542ff335056bd4c5862f1c01fa54955ff521840fcc4798fbf02c0550b3faba91359a221b1290583a69f8ce45573655d11d8c16d5ca23fa1b97dc9502247eccc85b27ac2f02ee6d76024dd17c76c3d71
```

```text
2^12: 0xa5b8ebc3d76ee03334da93a3fbc63a4378269d02531c1b29b22b63795e25db7a0f46693be4624b2c1d157f651c3226fe00b6d6c2011589f68badb272e52268fe0522da249e28b9beb325bc19fd0840c4cee4859b9c0ebe0791ae74444c725552
2^13: 0x8cb45dedabb4a944d3d53f842e2ed7214fcaf10c4138119e72f0a400d9c2615c8621e83f2d00f16cef5beca4c54422ce06524f9eea82bb7cc3d7a5f750b8761d4667c84556ecc9c1670f8013d4bad903131d714c9373ff4549c991aaa26aad3d
2^14: 0xb789d13d48b2969c493f11bb9b6612506273cf092abf9a104875af070d6f3797fbe8ed0f9f370b6d7c4b8fe753b6ed3501bdf76aa835bd2e05f4345cf8c5f14d99949d43be8e94b6986cf13576efc3d56de54f5ebbed5112990c6a9b1cf2cf1e
2^15: 0x80a7166c5804c2b0c621125605d4e9ed11a997b96d5e4ee0c3118271d4307e02aa50d08ef159da25388393c492331aeb0d9dbae554f7a84eb6fd9beaf97ef1989fb5f0231b1cfc5d4021ac730b7408725126a1a92e030fbfe8cb0c5333741239
```

![Album creation](./img/sc_02_ephemeral_create.jpg)
![Hardware destruction](./img/sc_02_ephemeral_destroy.jpg)

## 03 - Dog Dinner Dance Dynamics

@saint-rat fed their dog, Charlie, biscuits which they had scatted over the floor. They then used [a python script](https://github.com/saint-rat/KZG-Ceremony-Contribution-Code) and computer vision to track the location of Charlie and the biscuits as he ate them. This information was folded into the entropy contribution before destroying the SD card and flash-drive used by the Raspberry Pi for the contribution. [Read the details here.](http://web.archive.org/web/20230416141630/https://medium.com/@saint-rat/dog-dinner-dance-dynamics-a-peculiar-path-to-enhancing-entropy-in-the-kzg-ceremony-86a0b2a4eaf0)

|                       |                                            |
|-----------------------|--------------------------------------------|
|Ethereum Address:      |`0x051f77131b0ea6d149608021e06c7206317782cc`|
|Start Time:            |2023-04-06 16:00:00 UTC|
|End Time:              |2023-04-06 20:00:00 UTC|
|Client Implementation: |[go-kzg-ceremony-client](https://github.com/jsign/go-kzg-ceremony-client)|
|BLS Library:           |  [gnark-crypto](https://github.com/ConsenSys/gnark-crypto)|
|Write Up               |[@saint-rat's Medium article](http://web.archive.org/web/20230416141630/https://medium.com/@saint-rat/dog-dinner-dance-dynamics-a-peculiar-path-to-enhancing-entropy-in-the-kzg-ceremony-86a0b2a4eaf0)|
|Tweet by contributor:  |  [Twitter](https://twitter.com/saint_rat/status/1647598125480284161)|

__Powers of Tau Pubkeys:__

```text
2^12: 0x88b8e361e6912a4e9e01ed7adea527f2048278e2df20c21d8bc963ed9bfe2be59d6e6d0634656a924096b3da252a24b310c821c97613ff3fcfbf81eb37331c0d1f35d1fc68a40b9f2914f794b777829783e72539f47234b606291237974045e6
2^13: 0x89683cb512dca33e41e19b71354e461fe3f9c02985a64f5d6475d6b2b3d8bc923e35b4f465f99d23f03e7398157c111c0f0412868cd8a2dd33f55728e73cea2abb5f32c5cc13ae6d3f9b455ab8f4ace09d251476054722c2d373d2033b5d7fcd
2^14: 0xb228e137e41e89c07e6ca0d74bcb38a48a3f56de222e7b643d5e2d796a0f095d009bef7832c513be7e0422c5ce9b1c2603fd2614e6b9778387606c45c11083dd410cfb3e0dbef4f0461b3c72b6702577d1dbda4c2f64c71b288ea79157fd8e9d
2^15: 0x8e1cb174735fdb0c08218ac53ac91b02e3b3e58eb4c2fa860d08958c93b3e9b58f91a46eef5a594e709472d5e3eadf3c0d601086e4b5ed73ef2d0fc3c745e0ba716661f1bc1ed4570b12fbe49d66c950c9e9e4e97641a5f819b3c99397461f19
```

![Charlie is a good boi](./img/sc_03_charlie_meme.png)
![Charlie is a hungry boi](./img/sc_03_charlie_eating.jpeg)

__Additional Links:__

- [Video of hardware destruction](https://twitter.com/i/status/1647601259724275713)

## 04 - `CZG-Keremony` - a pure JS KZG ceremony client

[`CZG-Keremony` is a KZG ceremony client](https://github.com/dsrvlabs/czg-keremony) written entirely in JavaScript by the [DSRV Labs](https://www.dsrvlabs.com/) team. Under the hood, it uses @paulmillr's [https://github.com/paulmillr/noble-curves](noble-curves BLS implementation), so this is an end-to-end contribution done in pure JS. `rootwarp.eth` and @kim201212 performed an airgapped contribution on a RaspberryPi 2 before destroying the SD card.

|                       |                                            |
|-----------------------|--------------------------------------------|
|Ethereum Address:      |`0xa455150c6b91d08faa57dc664b916e1ddd1c4030`|
|Start Time:            |2023-04-11 08:00:00 UTC|
|End Time:              |2023-04-11 12:00:00 UTC|
|Client Implementation: |[CZG-Keremony](https://github.com/dsrvlabs/czg-keremony)|
|BLS Library:           |  [noble-curves](https://github.com/paulmillr/noble-curves)|
|Tweet by contributor:  |  [Twitter](https://twitter.com/rootwarp/status/1646717380868083712)|

__Ethereum Address:__ ``

__Powers of Tau Pubkeys:__

```text
2^12: 0xaf4de210b2cf4dd36cad375b215748cf226fbb1c6bc700c563881bd5cf5e6fd74b092f8bf32e3dffe3dfbec16032d88c0058184951521a32b02a5fd9c3cde14f2f78d2149b2e7e9d175c70408f2e89e0af9e4cc5b2712754e6185423b381b3b1
2^13: 0xb45ecbf063b0c558a726c18e9aba1b87a71cbc0553f696f8de1fd2c6eed741808ff17a9b6578b01d8eabb85ba70f7392101133305b11f8ae6b160da6e3c8ddc7c58b853e142ede847bb2c1fc61b4289ac251508af5d0b464f739f5192fc1e44a
2^14: 0xaba601aa8a77c671835670f1c2d402ea804b85b74f3be6cf186680515155ba4558d9d169bea9238eb1d5f4ffb3276d2415f5014175aec71e9a4c52fc716090734bb22ee1e7c8f425cc0e5d4996110f882e7f46cb12029cc93db72db317849a70
2^15: 0xb4f7516dbab3beccb7ddc2ec8852dc0c131e89b59becbec89d9e30ba6a121e7002e17da431924b5a21d47d215ac73a5e0e8bf8604909d9cde9115abd4ee1d859186461d8c53511cfc7114e1118fe899ab82dc4022adc41e70a08f07abffe2591
```

![CZG-Keremony](./img/sc_04_dsrv.jpg)

## 05 - Improvised Theatre

Members of the Student Theatre Association in Eindhoven, [Doppio](https://doppio.nl/), recorded an imporv theater performance as a source of entropy for the ceremony. The performance comprised of both acting and singing using the structure of a soap-opera and a "revolving door" to guide the performance. Read more about what they did on their [blog post](http://web.archive.org/web/20230502173054/https://github.com/ThomasdenH/ethereum-kzg-ceremony-documentation).

|                       |                                            |
|-----------------------|--------------------------------------------|
|Ethereum Address:      |`0xb70aa3d2b6dfcaa804c45ed0bfeb785562db42dc`|
|Start Time:            |2023-04-11 20:00:00 UTC|
|End Time:              |2023-04-12 00:00:00 UTC|
|Client Implementation: |[go-kzg-ceremony-client](https://github.com/jsign/go-kzg-ceremony-client)|
|BLS Library:           |  [gnark-crypto](https://github.com/ConsenSys/gnark-crypto)|
|Write Up               |[Write up on Github](http://web.archive.org/web/20230502173054/https://github.com/ThomasdenH/ethereum-kzg-ceremony-documentation)|
|Tweet by contributor:  |  [Twitter](https://twitter.com/ThomasdenH/status/1645911736896110594)|

__Powers of Tau Pubkeys:__

```text
2^12: 0x93d7ba163530c3d6f70b3f89d0bdd4986e53aad52d2279c75ee967ee080f32209a960a7d3070c41b1c94db0e4633c30c1814da27415289f989a524602c3455f8d82756b2c8c9f2e77a2c4e8bc2460ef137fcc3c5f46d4f16b1ab39b1345ac697
2^13: 0x87ed4d56364f6348fab07a27c6676f540ab9cddce390efcf9ee84b9cca2a0ec391be5bcfaae127259dfdc6388680dd75084c99df9dfe27dc089fc8016bc0079e36ea94536056f2712e4c7644f7366c2467b8d4a8f4bf0351473443d78f9de5b8
2^14: 0x8cc3102e8439e4e755544183af743914aec47e341a0a13b2ff857939fd16e0da7f3e741266192ed565e26dde3bca9a17192556efe0c54bacf20826a50cc7478c06fe5c15b379be2d96719db87435ff6622bfc699f77a09a9e86e0ff843cb28bf
2^15: 0xb46c6e844ca35349147f6dbf3bcde313c84cb9992d9593d842dc254220219ec75fb255ce45f762873ed60208ae6ba0c200ac0cca920f15b2250c4c21b8e1793d6fd26810b87559f0516fc28e80620318e83b1afbcda0cb3beb6f4b32e48fa811
```

![Improv Theatre](./img/sc_05_improv.jpg)

## 06 - A Calculating Car

[Stephen Solis](http://web.archive.org/web/20220805222403/https://stephensol.is/) drove around in a car equipped with a [Comma 3](http://web.archive.org/web/20230418103833/https://comma.ai/) self-driving module. He then recorded the data from the car's ODB port to an NVMe drive which was destroyed after using the data as an entropy source.

|                       |                                            |
|-----------------------|--------------------------------------------|
|Ethereum Address:      |`0x192ccacdd6da99463e1e8a76223ea07a6cde3479`|
|Start Time:            |2023-04-12 20:00:00 UTC|
|End Time:              |2023-04-13 00:00:00 UTC|
|Client Implementation: |[go-kzg-ceremony-client](https://github.com/jsign/go-kzg-ceremony-client)|
|BLS Library:           |  [gnark-crypto](https://github.com/ConsenSys/gnark-crypto)|
|Write Up               |TBD|

__Powers of Tau Pubkeys:__

```text
2^12: 0x932a946bad415d52f5df4a33400343f234207ac228356e31402d7dc59fa8d070a40fec9845f227473308b928e47d15e50554eb9d98784099ae9918a4c6c69402e1f5123a78a97d4d054fee94d817ea043b3f3eaf9af259ddd209d5e0b7d01ca3
2^13: 0xb3a1d9379b96cdb29aa8f381555efcda1273e9ea8168e9d43e7bf62d461100ec905da84251799e6201c808e670da42d90784856ff819e797ca39ad7510152c048374df8f748327b9a2d5c8f10e220046cb83b71e6eb516bfa627af5e367436e3
2^14: 0x9642b7ea0df52d7c4e0a35b385659551887d6e5fab5458d89cd898b382f6dd2aa82ce49d8db4921ad85741fb347b1a93057b8e1e84687a40fb659550fb1db4afe6924fec2ae1d73efd628f7dc0f9e343319971b7397baa6e24949c1cc243461a
2^15: 0xa5fb2e8b94cc38941e392902875ea3d8d2e2de9a848184ea06a5fe38ba3021b243e52f26019cf849ac624ca20fae5fbd14b7657c4f66922d59412cd7cfb436946f40c0f96e3c7d7a2344336888f6ab905fca9c66717edc69887f227ef09be141
```

___BLS Signatures:__

```text
2^12: 0xa684f7c8f920ec8476783cee786b56a50e98810ea7148c8bc855e798c20de1aa6decf0efc8742599691f941c6690af53
2^13: 0xa602fc258c1944074a0755a3b37394335c5d3eb56cb29ffb03acd4d14bf376c4aebf3f6f2033c6ade2acfe09c3f76916
2^14: 0x866f1f90bf1ed70ed7bfe5d81ba168697899602d7a769c0e3f82b3b5b7deb061d9adbe75e3d1642736deaad65c5e73d4
2^15: 0x85906813236394b76273829318c84552aa93e134d58757c6329ef3231918444f32a3da1d1422248c486e7d151af9599b
```

![Self Driving Car dash view](./img/sc_06_selfdrivingcar_dashview.png)

## 07 - A noisy city

Jordin Coppard recorded the noise of Sydney from a balcony and used the raw data stream as an entropy source.

|                       |                                            |
|-----------------------|--------------------------------------------|
|Ethereum Address:      |`0xf4BA33f683aCA91128A8915de6664cB662e59af2`|
|Start Time:            |2023-04-13 04:00:00 UTC|
|End Time:              |2023-04-13 08:00:00 UTC|
|Client Implementation: |[go-kzg-ceremony-client](https://github.com/jsign/go-kzg-ceremony-client)|
|BLS Library:           |  [gnark-crypto](https://github.com/ConsenSys/gnark-crypto)|
|Write Up               |TBD|
|Tweet by contributor:  |  [Twitter](https://twitter.com/wz__ht/status/1646414895997648897)|

__Powers of Tau Pubkeys:__

```text
2^12: 0xa9138a78d90473eb2e4d5a2bb141318e7f0a4045e6651a23e0e96a0da596cca944ebc6614e63c2dfdf33e243d072d3f10fe361d14d27b61c956a0765b1efaa456b3e401334c900391a403f5013dabc9099de357a286274f53b8399355534d3b2
2^13: 0x83209b8e3b4b9c85398d1f452d8607b2c0e9b98085484ffc42465237d10324bfc54bbba7064b0a407ce21effd2cf294c087068391b57f9ad6ee65b875e36ecc442f7c2d0997c9dd238d59da72a73cc236320529ac1743ca566dbc28b7b4180bc
2^14: 0xa8705cca3841b4cb715613e8cc856cc765b8f48c6fe4ce157fd98e11ac52cbc602e476dcef39c6d8f4dbbc63686ba41e0e19b53b4f89f3e99f79b86887e30e28dfa63aeebf7577940b13d259be1a09f08016d14ca4b875d42f56998d6bef2c9b
2^15: 0xaf2a56a7e5234950bcde7cc3f31fdb6e5fb8ec7528d05e5b58b0faf696c2a8912fa2a8f20984cd77596fda9da45384e803f8244172ba76300749b0c08754f62ac233e41a14e097cfd67899dfa000e741b88ac995eb9a1865de2400078be06a76
```

![Sydney can be a loud place](./img/sc_07_noisy_city.jpg)

## 08 - Exothermic Entropy

The [Mach34 Team](http://web.archive.org/web/20220910211520/https://mach34.space/) detonated 4 pounds of a binary explosive called Tannerite and used a [RaspberryShake](http://web.archive.org/web/20230410210102/https://raspberryshake.org/) to record the seismic activity as entropy. Afterwards, they destroyed the storage media with a rifle. Read about their escapades [here](http://web.archive.org/web/20230502181323/https://medium.com/@outsideranalytics/exothermic-entropy-884997e28024).

|                       |                                            |
|-----------------------|--------------------------------------------|
|Ethereum Address:      |`0x147d740aaf617b46e85304d2590acc20a90cee7c`|
|Start Time:            |2023-04-13 20:00:00 UTC|
|End Time:              |2023-04-14 00:00:00 UTC|
|Client Implementation: |[go-kzg-ceremony-client](https://github.com/jsign/go-kzg-ceremony-client)|
|BLS Library:           |  [gnark-crypto](https://github.com/ConsenSys/gnark-crypto)|
|Write Up               |[@outsideranalytics Medium article](http://web.archive.org/web/20230502181323/https://medium.com/@outsideranalytics/exothermic-entropy-884997e28024)|
|Tweet by contributor:  |  [Twitter](https://twitter.com/mach34_/status/1647055219422040064)|

__Powers of Tau Pubkeys:__

```text
2^12: 0xb4def5b4585f28b55ea240ecb018b1e0291ef69860629e8fc6561a5a87d45d988c0f156c888c0a786dba4c23df0e6a4c11b1827f2d35466af57dbafd9b9487a0c194f2fbb68ed16da790804c8764016bacea9f9830871bd77643da3574d90c47
2^13: 0x84a644c897e4dad1f6626c63c93ba3cf55668fed60dbcab652b5adce691b4908af3b51ce739ecade41902c99c1fe075318733e03b785947e4f500ccc2146604d74b502e229c3ccf3627b03a4bbdc3a27a0ab3eb3bbbfab15599889ec2432613e
2^14: 0xa5e0d95150c9fca0d55f729c5b359622f297bb1a5400fbcbfb65b797441df1f2caa00c6b168df639a754e90c826d7fc311782317901b810c8ef1081887ea24adf2a8ada2690a93211486ec390cb862f93af60f1c1110aa157e0c9fbfadd871d1
2^15: 0xb03b424f983ffa7a36426230f4a55c100cfc1c07cedcb586a0f0a4f3e6bc3a9bf0fff0f72acfcc4d7bf5fc137ec55940022f1858ef9668b8c749602bdff2eaa10c20f2f33c19e35484978751d104d2001cdbb36014f2fb1a7abd4718f60017ff
```

![Boom](./img/sc_08_rifle.png)

## 09 - The Sferic Project

Digital artist, [Matt DesLauriers](http://web.archive.org/web/20230417162857/https://www.mattdesl.com/) sampled the Very Low Frequency radio (300 Hz and 13 kHz) radio spectrum on southern coast of the United Kingdom to capture lightning strikes and other atmospheric noise collectively known as _sferics_. This data was then fed into the ceremony as a source of randomness.

|                       |                                            |
|-----------------------|--------------------------------------------|
|Ethereum Address:      |`0x32262672c6d1b814019f4ca4e2fc53285a919704`|
|Start Time:            |2023-04-14 12:00:00 UTC|
|End Time:              |2023-04-14 16:00:00 UTC|
|Client Implementation: |[go-kzg-ceremony-client](https://github.com/jsign/go-kzg-ceremony-client)|
|BLS Library:           |  [gnark-crypto](https://github.com/ConsenSys/gnark-crypto)|
|Write Up               |[Matt DesLauriers' blog post](http://web.archive.org/web/20230421084214/https://www.mattdesl.com/sferics.html)|
|Tweet by contributor:  |  [Twitter](https://twitter.com/mattdesl/status/1646998422438682625)|

__Powers of Tau Pubkeys:__

```text
2^12: 0xb3b911dc87eca0dbd112683c0b4a2de75c7ed54dacecf7e39ad195635f184500b0dc1b1e76e91fc618c271aa90f0c5d1004a62a6770a1c124465b33742f6ce6eeb396f037197a39005e767072aad4d2ebbb4e2a4f2924a2fb75afc2774d1df97
2^13: 0x8275ccada94f3eeef20dde781243fc7b0229e5607b9b1a720a60de25984c8c7dafcfdfa54a6326b27219e94480973ac213560c92a8225c9d9d081459679d648e79552875807c278c2656f12abb267b10d30ff1f060428bc88536b46219147ee6
2^14: 0x8f2287c6b5d5faeb6860bca0fa66c979117f44d7b1aaf01120c167e650bf0483067d4bd6e72e241804fcc6d18a885a4206683ee3459db5ce4e10167a675dec39ff840ee2a7f392f9bd175f7523d2c01a6c3a39268584ccaf0392f537d823bbcc
2^15: 0x96a1bbb71fdaa3d21438505bc651d1033011635946685e3f48e17d3fbbc1fe0f22e92fa359572eaf536edf4d17ac49f307ac3c8c4986d74d5e2edbb5277ee2a5fbc65250bbc1497ba20d51268647e5293677221854202eb40acf4f72b5029a98
```

![Measuring atmospheric noise](./img/sc_09_spherics_sampling.jpg)
![Contributing spheric entropy](./img/sc_09_spherics_computer.jpg)

## 10 - The Great Belgian Beer Entropy Caper

`heeckhau.eth` and `sponnet.eth` contributed entropy by video-recording the pouring and fizzing of Belgian beers using a webcam and an [AVADO i5 box](http://web.archive.org/web/20230411100207/https://ava.do/) before destroying the USB flash drive used for live-booting Ubuntu with a hammer.

|                       |                                            |
|-----------------------|--------------------------------------------|
|Ethereum Address:      |`0x8dd4e78567201d1d9f8459a265f4d0ae81ae3c83`|
|Start Time:            |2023-04-14 16:00:00 UTC|
|End Time:              |2023-04-14 20:00:00 UTC|
|Client Implementation: |[go-kzg-ceremony-client](https://github.com/jsign/go-kzg-ceremony-client)|
|BLS Library:           |  [gnark-crypto](https://github.com/ConsenSys/gnark-crypto)|
|Write Up               |[Write up](https://docs.ava.do/specials/kzg_ceremony_ethereum/)|
|Tweet by contributor:  |  [Twitter](https://twitter.com/heeckhau/status/1647248232660058113)|

__Powers of Tau Pubkeys:__

```text
2^12: 0xb4df712ca54b240fbc81a5afb52409fa398d8699fa8738825aa68ef9209a813bffced68d86a18a2f6995f5c803d86ce40d4f4eb729a78fbfef2ebe400ebdd847d07b95f197dba5eb8784ec49e6ac6c36990a539f6d11994d43a7dd157648977e
2^13: 0x802a188a831aaee5b64121ea1c31f385a5f0f68145b004fbbfa5ce240396122cf137d7a2c7e0e09a199994fbb350462601008062a60535fd078c978ad7603e2c0e73ab121807b2410653c332282330a59ea1faa8935c69ec08d8c8c3cad44401
2^14: 0x9013192130cc5f1b4476488b8ea2b6e0d6e1dd377faec09afd66d3bf09b99a274206f556acf1b8b78b095a3e0ea16c7f06ad803e1294edb81a890ec290350dd3964e10ad0980d1b306551ca192960149bf1daa6fb381cdae3a68e6a911964812
2^15: 0xa45306ac93de744a34d30a65799ff37eb91e495e3a90299227b818c70a4a6cba2f1e29024d8c3e7adae50dcb96e9ff33195167e902d97e3efc73388c2374265c526cb88bd9bff46eef4080470d17dd46e37d6bfc1c9cee35739ce7e537870fc0
```

![Recording the bubbles](./img/sc_10_beer_recording.jpg)
![Contributing spheric entropy](./img/sc_10_beer_usb_destruction.png)

## 11 - KZGamer - summoning Dankshard with a dice-tower

Justin Florentine built a dice tower that could both collect entropy for the ceremony and help determine the outcomes of his table-top games. The dice tower was a sealed box which rolled the dice before collecting them in a sealed chamber in which they were photographed by a Raspberry Pi (and camera). Then computer vision was used to read the dice which were used to determine the success/failure/damage of a given roll while adding the dice values to an internal entropy accumulator. A trapdoor then opened to return the dice to the player. By the end of the game, 1024 bits of entropy had been collected and the SD card used in the Pi was burned until destruction.

|                       |                                            |
|-----------------------|--------------------------------------------|
|Ethereum Address:      |`0xf51d203536ea8b5bfbc06b3a1c21514766b22bb1`|
|Start Time:            |2023-04-15 00:00:00 UTC|
|End Time:              |2023-04-15 04:00:00 UTC|
|Client Implementation: |[go-kzg-ceremony-client](https://github.com/jsign/go-kzg-ceremony-client)|
|BLS Library:           |  [gnark-crypto](https://github.com/ConsenSys/gnark-crypto)|
|Write Up               |[Justin's Write up](http://web.archive.org/web/20230504180930/https://hackmd.io/axUX8pFUQD-yCiBzQEDrYQ?view)|
|Tweet by contributor:  |  [Twitter](https://twitter.com/robocopsgonemad/status/1647022574595895301)|

__Powers of Tau Pubkeys:__

```text
2^12: 0x9157bfd6d53e6f9cd427aa84acfe47e7f1224ab99ac2c606ccea8dec3ba85a73d3b29c74422461697e9d86e36baa7f8d02add99798a40e2f32c2cd7185b13ad86f57fb7df418c708727d9ff2f85cc220f66353408151075785caf78f3b6c4dbe
2^13: 0x92ae7793b9ba21e8dcfa88e4722acd8b5282d0ad9f9407db13b966797d8a98474986e3beb0d6271fb4fe68ea485dd8ff05144addcf1af56f69a2c26ad5e6009b481e77f431247a03c22e458da0f5264e1d0db7e3e5aa6f1fc93cf539271b77fc
2^14: 0x908b21c002bb0a336e8c22da6c5f3ae688c7319f72045eff8817233fbb3c29a652f04a435e4392507462b4530f80db5c102844255ec594c1b15b3b2ae9f3a3797436846f754e8769f4c5450902d2f3d704971fb998881aeea998c64d37198391
2^15: 0xa64a105c21f2d9cff3799ef38203ae6da23b12be6949ab8dd136244de4af918b6bdb4d69537af464c3b3a156f89655720b827a331ad71d3a43ce9420b7b81be6e81b69009824de01b618ea65d2512da82215d75c99fbe9e010df5c51279416e6
```

![The dice tower in all its beauty](./img/sc_11_kzgamer_tower.jpg)
![Gaming table with tower in the background](./img/sc_11_kzgamer_tabletop.jpg)
![Burning the SD Card](./img/sc_11_kzgamer_sd_burn.png)

## 12 - Catropy

[Proof of Cat](http://web.archive.org/web/20230501054531/https://proofof.cat/) or Catropy is a project to collect entropy from cats playing with a ball. This was done by embedding a custom PCB with an [ESP-32 microcontroller](http://web.archive.org/web/20230415171816/https://www.espressif.com/en/products/socs/esp32-c3) and an [MPU-6500 6-axis IMU](http://web.archive.org/web/20230307183944/https://invensense.tdk.com/products/motion-tracking/6-axis/mpu-6500/) into a knitted ball and handing it to cat (or human). The ESP-32 would then collect data from the accelerometers and gyroscopes, hash it into an entropy accumulator and serve that entropy over WiFi to the server performing the PoT calculations. Visit [proofof.cat](http://web.archive.org/web/20230501054531/https://proofof.cat/) for details on the multiple contributions, hardware, software, a [video](https://www.youtube.com/watch?v=Nqg8KdmP-_g) of the contribution, and how this project went further to support cat shelters.

|                       |                                            |
|-----------------------|--------------------------------------------|
|Ethereum Address:      |`0xdb08c59302e8449fb5f2f6ccf7dde974e678a31f`|
|Start Time:            |2023-04-15 08:00:00 UTC|
|End Time:              |2023-04-15 12:00:00 UTC|
|Client Implementation: |[go-kzg-ceremony-client](https://github.com/jsign/go-kzg-ceremony-client)|
|BLS Library:           |  [gnark-crypto](https://github.com/ConsenSys/gnark-crypto)|
|Write Up               |[proofof.cat website](http://web.archive.org/web/20230501054531/https://proofof.cat/)|
|Tweet by contributor:  |  [Twitter](https://twitter.com/0x_Ytocin/status/1647291053429456903)|

__Powers of Tau Pubkeys:__

```text
2^12: 0x90bb2d0b11f285ed5a9cf06ed435c42dec65e98f7d31a6569d21360ed62ad2e6160d8eec56bddb32c6c0c50b8333908016d1d3684208522be38e5c4d968800fa09d048a5711a5d286c31e5b39861ce2adf65ee4c401569eea12a15a9be2d8125
2^13: 0x8e9ea8bd5cde8c3ec463533850373b1403f906292fb87758e09e42cae4836a3d79ea210f5d117e99b9b84af2e9978ecd197e2a9488c7eaef27e54a8fd4c77190b844edf8378b46a84fef2a0054cf1d53371944edb1a409b2d4dfcdecc3523ae1
2^14: 0xb258f5e8c3b413f594a1e97f797d246a12c0e669bb6d75cbb5fe97e467528fdc3429beabb51b352d162f768a33d366bf022a0a2f35a6ab70f714bd3bbccbb8dff3751bfb86243e18a81a92dba5870d692c910ae757675106a0dac41682382798
2^15: 0x995bc110eff9b401282d4674753f8dff975d78601f1a3695e1c14f99af0b58bf8acf47c1bfff5e3d9100fef5bb2b8a140a415551034eb9494775c512ee5cc9fc47f031dad6b454f96ecd8632e94306ca8f4decf67c6e6a3974a46cba586d84dc
```

![Catropy PCB](./img/sc_12_catropy_device.jpeg)
![Proof of Proof of Cat](./img/sc_12_catropy_contribution.png)

## 13 - `srsly` - an iOS KZG Ceremony client

`srsly` is a KZG Ceremony client (and BLS library!) for iOS written in Swift by @srikrishnamurthy. The library is available on GitHub [vishady721/swift-kzg-ios-client](https://github.com/vishady721/swift-kzg-ios-client).

|                       |                                            |
|-----------------------|--------------------------------------------|
|Ethereum Address:      |`0xdf369cde73ce4d75deba0d9a6f67873ea9350b9b`|
|Start Time:            |2023-04-16 20:00:00 UTC|
|End Time:              |2023-04-17 00:00:00 UTC|
|Client Implementation: |[swift-kzg-ios-client](https://github.com/vishady721/swift-kzg-ios-client)|
|BLS Library:           |[custom BLS library](https://github.com/vishady721/swift-kzg-ios-client)|
|Write Up               |[Witnesses Published on GitHub](https://github.com/vishady721/swift-kzg-ios-client#contribution-receipt)|

__Powers of Tau Pubkeys:__

```text
2^12: 0xb2c3a994728990489e9b4baccf2ca2d178478b8adb60e9d339bb8d6305d9a726e20be519208b03189c175d6b1e1231c81079cca38a8fef5b576b714225dab3e46241d18510b19de9639b84e136f3fef055a60ef610ba2daeaf6df03583b80665
2^13: 0xb32320ac9ea45e0e7e83809e441166ff82fb55eaf5b617f04b7971c0972780f41ffab86d5e8b729c4886acf25212cd6102df3edee2367278370ffe71f7021d7abb4dc2b10fb01f965c34c02f249f93b2c2e1de250cd54c094be8561e004f0678
2^14: 0xb9dcedee0b1467900783e50cdd08f9bc849af9cc9ae7f81df3aeecaaec2df83c68525c7fe90adf82a3e6999dad693c451166b3f5304258713dff5faf73ee4d7eedadc18ae80150fe44252b33f4820cb52feb6b1045db54668f2b3a5bd2654993
2^15: 0x8a000e8d0c2a591585307e1a98558f7dbab8d6867297870d70c8d66efb4c72972b84f233bf6b2938c5c2b9d6d009489605a6b547b6aa91bdd0b3fb2c799ccd5774131c1e12d993cd25bf16b682e95c2616e90be0a7302a0b126dedaf16ced798
```
