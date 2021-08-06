# Real World Concurrency Bugs in Go

Forked from https://github.com/system-pclub/go-concurrency-bugs , for the purpose of sorting with GitHub links.

## Blocking Bugs

### boltdb

- https://github.com/etcd-io/bbolt/commit/defdb743cdca840890fea24c3111a7bffe5cc0a3

### cockroachdb

- https://github.com/cockroachdb/cockroach/commit/1cc699802557f67d4464de391b7350a527f9f445
- https://github.com/cockroachdb/cockroach/commit/27e863d90ab0660494778f1c35966cc5ddc38e32
- https://github.com/cockroachdb/cockroach/commit/822bd176cc725c6b50905ea615023200b395e14f
- https://github.com/cockroachdb/cockroach/commit/9bf770cd8f6eaff5441b80d3aec1a5614e8747e1
- https://github.com/cockroachdb/cockroach/commit/cab761b9f5ee5dee1448bc5d6b1d9f5a0ff0bad5
- https://github.com/cockroachdb/cockroach/commit/cb65190f9caaf464723e7d072b1f1b69a044ef7b
- https://github.com/cockroachdb/cockroach/commit/d064942b067ab84628f79cbfda001fa3138d8d6e
- https://github.com/cockroachdb/cockroach/commit/d9b384b05ebfa8ba6c679c8c0c6034357416c2d7
- https://github.com/cockroachdb/cockroach/commit/de89a847175062dbc12e274b19623193cd69685b
- https://github.com/cockroachdb/cockroach/commit/ed6a100ba38dd51b0888b9a3d3ac6bdbb26c528c
- https://github.com/cockroachdb/cockroach/commit/ef906076adc1d0e3721944829cfedfed51810088
- https://github.com/cockroachdb/cockroach/commit/f1a5c19125c65129b966fbdc0e6408e8df214aba

### docker

- https://github.com/moby/moby/commit/03ea2166b66632ee7cdd824d7acd87b15c9bccb2
- https://github.com/moby/moby/commit/0d9e54367f7bf7da9670de723d533eaa920868c8
- https://github.com/moby/moby/commit/2938dce794be7559ba73b4e9630015020a7fa937
- https://github.com/moby/moby/commit/2f16895ee94848e2d8ad72bc01968b4c88d84cb8
- https://github.com/moby/moby/commit/2f4aa9658408ac72a598363c6e22eadf93dbb8a7
- https://github.com/moby/moby/commit/2ffef1b7eb618162673c6ffabccb9ca57c7dfce3
- https://github.com/moby/moby/commit/3037e4f7c4eec06cf3a5afca6f58ec58b4bdd63e
- https://github.com/moby/moby/commit/37addf0a50ccba51630368c6ed09eb08166d6f48
- https://github.com/moby/moby/commit/42360d164b9f25fb4b150ef066fcf57fa39559a7
- https://github.com/moby/moby/commit/4d009084de8cad94a180130eb57efa2a98df6d98
- https://github.com/moby/moby/commit/4d2d2ea39336aade783c5c415b83d129bdd339bb
- https://github.com/moby/moby/commit/58befe3081726ef74ea09198cd9488fb42c51f51
- https://github.com/moby/moby/commit/6cbb8e070d6c3a66bf48fbe5cbf689557eee23db
- https://github.com/moby/moby/commit/89b123473774248fc3a0356dd3ce5b116cc69b29
- https://github.com/moby/moby/commit/a44fcd3d27c06aaa60d8d1cbce169f0d982e74b1
- https://github.com/moby/moby/commit/a69a59ffc7e3d028a72d1195c2c1535f447eaa84
- https://github.com/moby/moby/commit/bd2b3d363ff7c46e01cce4e6a41d41f24a0047da
- https://github.com/moby/moby/commit/d3a6ee1e55a53ee54b91ffb6c53ba674768cf9de
- https://github.com/moby/moby/commit/d55998be81973be5b083eed56b223c8ce98ce073
- https://github.com/moby/moby/commit/da28210a157a3bf5662f1a049bb10f9b69d2a5a2
- https://github.com/moby/moby/commit/f2d384fca6fa08da13fdc01c7991e8e35b081198

### etcd

- https://github.com/etcd-io/etcd/commit/0cb304ec61019c5ff2f6260245ef30fb6dc9711a
- https://github.com/etcd-io/etcd/commit/120020fa9c3d4b6c98d7beb863ac4c6bfe4d499b
- https://github.com/etcd-io/etcd/commit/1b1fabef8ffec606909f01c3983300fff539f214
- https://github.com/etcd-io/etcd/commit/1d8813052292e6053957fae01d080fde9717f3fc
- https://github.com/etcd-io/etcd/commit/22797c718504868665b78f143a595138cb521edf
- https://github.com/etcd-io/etcd/commit/36f5b713bf4cad4702163ed9476ea83de9059b3d
- https://github.com/etcd-io/etcd/commit/7618fdd1d642e47cac70c03f637b0fd798a53a6e
- https://github.com/etcd-io/etcd/commit/7afc490c95789c408fbc256d8e790273d331c984
- https://github.com/etcd-io/etcd/commit/7b7feb46fcf13da75f93797740ffc6034bb585ff
- https://github.com/etcd-io/etcd/commit/87d99fe0387ee1df1cf1811d88d37331939ef4ae
- https://github.com/etcd-io/etcd/commit/8baaa06cce9e58548f60e6e9b21c9af3d42580bb
- https://github.com/etcd-io/etcd/commit/91ff6f30b50a14158ec10cdd24836d775a336f52
- https://github.com/etcd-io/etcd/commit/9497e9678cdc64785847993c96ff2748e09ef9a1
- https://github.com/etcd-io/etcd/commit/ae062a0825a4100d0cf9ac7c8bb0fa1ca69c6814
- https://github.com/etcd-io/etcd/commit/b2a15ec327ead1caf6d6983092dae17e09c88dd1
- https://github.com/etcd-io/etcd/commit/b7cf2385e6874d07f32f183007e50f4448b7e3a2
- https://github.com/etcd-io/etcd/commit/c43831063411d923566f1c607933c1d721c1f5f2
- https://github.com/etcd-io/etcd/commit/cb9a3e04b141d150a370f1e6329428b621742041
- https://github.com/etcd-io/etcd/commit/d21d2e6624bc5400e52baa45804668f5f9b6a161
- https://github.com/etcd-io/etcd/commit/de008c8a4ac327eee481fcc0245f55de7b393351
- https://github.com/etcd-io/etcd/commit/fb12a4e412fee79c8c59277f7e49d5cca5ed901f

### grpc-go

- https://github.com/grpc/grpc-go/commit/262ed2bd6d1c8cbaa14b43c3815d2e01e4f65ca8
- https://github.com/grpc/grpc-go/commit/27b2052c9524abc45ae991d6a402ddb91f06ba03
- https://github.com/grpc/grpc-go/commit/47fc4a2936669af9ec8f851be845f2d4c7bcca18
- https://github.com/grpc/grpc-go/commit/484b3ebb4ab56d3decc8240d599718bdbefcf7eb
- https://github.com/grpc/grpc-go/commit/4bbe223b12805ab25acbb9d2cadfab2ec9d04bb6
- https://github.com/grpc/grpc-go/commit/4e56696c6c5a8cd7b711a1eb8936463559361da5
- https://github.com/grpc/grpc-go/commit/5a547ed72c09faf4050739d54caea1d51f4d276d
- https://github.com/grpc/grpc-go/commit/7df48bee8829276b13ef52bff4e1c47b9d55cd7d
- https://github.com/grpc/grpc-go/commit/c29d6389e66f5da1a226df88607857aab4db9f7a
- https://github.com/grpc/grpc-go/commit/ceacfbcbc1514e4e677932fd55938ac455d182fb
- https://github.com/grpc/grpc-go/commit/dd5645bebff44f6b88780bb949022a09eadd7dae

### kubernetes

- https://github.com/kubernetes/kubernetes/commit/010a127314a935d8d038f8dd4559fc5b249813e4
- https://github.com/kubernetes/kubernetes/commit/04e2deeb287f7d60372ed853a75acfff3668cedc
- https://github.com/kubernetes/kubernetes/commit/0aee25e06527993c59f3159e0cf3ff4342e169cd
- https://github.com/kubernetes/kubernetes/commit/214d0189113347a5475c227feff23330196613f5
- https://github.com/kubernetes/kubernetes/commit/435e0b73bb99862f9dedf56a50260ff3dfef14ff
- https://github.com/kubernetes/kubernetes/commit/5cc841a337fe2a8bcfe29450a6bc4650d9e348c2
- https://github.com/kubernetes/kubernetes/commit/64ad3e17ad15cd0f9a4fd86706eec1c572033254
- https://github.com/kubernetes/kubernetes/commit/681d153050930f67945fc308ad10566ec299edd5
- https://github.com/kubernetes/kubernetes/commit/82afb7ab1fe12cf2efceede2322d082eaf5d5adc
- https://github.com/kubernetes/kubernetes/commit/97f4647dc3d8cf46c2b66b89a31c758a6edfb57c
- https://github.com/kubernetes/kubernetes/commit/991674380b7773d73afaeafeac6242bf3b6e6001
- https://github.com/kubernetes/kubernetes/commit/9a2089adc8b60e9a33ca59cdc931e21d956f1ff8
- https://github.com/kubernetes/kubernetes/commit/9b00b7ef354725ffa57b3087c8add1990183f205
- https://github.com/kubernetes/kubernetes/commit/a12b7edc42c5c06a2e7d9f381975658692951d5a
- https://github.com/kubernetes/kubernetes/commit/c1b19fce903675b82e9fdd1befcc5f5d658bfe78
- https://github.com/kubernetes/kubernetes/commit/d3639aff7397dd0f0d3553b82043401ff834a356
- https://github.com/kubernetes/kubernetes/commit/e98c8e7685f4475e091f9186606098039c2fc250

## Non-blocking Bugs

### boltdb

- https://github.com/etcd-io/bbolt/commit/7fb06feea4012543b6a1b0726a09e9a4c4a84933
- https://github.com/etcd-io/bbolt/commit/c69cb102ce8f7609b57f75d0ccb10862167001e7

### cockroachdb

- https://github.com/cockroachdb/cockroach/commit/0a373bf1c1761d3ed1b18a58b9007161ac1d84ab
- https://github.com/cockroachdb/cockroach/commit/10a1f2fbccf2d44a6713897e1eeaaecd3a736fad
- https://github.com/cockroachdb/cockroach/commit/13b7170638509279be231aa23c714c91635e9ac6
- https://github.com/cockroachdb/cockroach/commit/2e360787f013010f39ee0804c772d216d546772e
- https://github.com/cockroachdb/cockroach/commit/380e8e1dcee91861a8a96aa6a0600c1d8500c902
- https://github.com/cockroachdb/cockroach/commit/38dfe4326de2a1c4d2881f227b94923017d95ce7
- https://github.com/cockroachdb/cockroach/commit/4edda446686e8d6cd358c1db685bf27aaf680a06
- https://github.com/cockroachdb/cockroach/commit/53f62683103345d0e73d968486940a8bdcc760cf
- https://github.com/cockroachdb/cockroach/commit/626d5bf221530a192b74914fbc138fd5b3a8dc44
- https://github.com/cockroachdb/cockroach/commit/76dbbc74da7bbc04b07b5cb0c18b9b4cf8d18433
- https://github.com/cockroachdb/cockroach/commit/81e5855770d4f80dd9919278049aee5cb4afe47c
- https://github.com/cockroachdb/cockroach/commit/9ef72e06cf4faf47bc7d789a18bd6a9755968aa1
- https://github.com/cockroachdb/cockroach/commit/d5a604c99d9e9741f7f2242de204abde1b47c2d9
- https://github.com/cockroachdb/cockroach/commit/e7d357b97777afa2c78a0321ef57eb1deeb3fe06
- https://github.com/cockroachdb/cockroach/commit/e9631ff35d1418bd9cb18e56e3180bd195c64f89
- https://github.com/cockroachdb/cockroach/commit/ef4fa8a47a438acbd0e3c402dbfd34ebd0351a42

### docker

- https://github.com/moby/moby/commit/1670914b8a56ab8e6ead38739fddb416b61e444f
- https://github.com/moby/moby/commit/2704fd9156bfb0fb8dc16c42902bb18ea5aa94a9
- https://github.com/moby/moby/commit/27b060492c483d61b76f18a529c94a71fdfc5312
- https://github.com/moby/moby/commit/2d21996eec8d3e6100f19fa0d0fa7adad25285ca
- https://github.com/moby/moby/commit/378f0657f963fa6c854643571e4fe83628466c01
- https://github.com/moby/moby/commit/46b1194d996f6535e657bcb88428303305d3fe68
- https://github.com/moby/moby/commit/4d200cd6938c1416e34bf43576b0d528b73e8ba3
- https://github.com/moby/moby/commit/4e262f63876018ca78d54a98eee3f533352b0ac9
- https://github.com/moby/moby/commit/52c0f36f7b7aa794932fa41dfe50dc85f78e6146
- https://github.com/moby/moby/commit/6ef8057700b63e2c5fd5cec206915ef1f2088578
- https://github.com/moby/moby/commit/825e3a66a419038600024be7dfc5ca24426444f0
- https://github.com/moby/moby/commit/8f6a14452dfd88aedc8ac9577a98c38a555baadc
- https://github.com/moby/moby/commit/985175fd8f8f662d5067bd62a89330e9a437375c
- https://github.com/moby/moby/commit/ab533f06510a14a023c056604f9520741073acd3
- https://github.com/moby/moby/commit/abfdaca3f86d7951693697fbd849078d6b406478
- https://github.com/moby/moby/commit/b32478488ce6d373e44bb8a6c9cb986c773ad48e
- https://github.com/moby/moby/commit/b38cee9f9c79d1f12001348303b78462d99664ed
- https://github.com/moby/moby/commit/c1ad02ccc8791b3c517aa37223d27792863cbf17
- https://github.com/moby/moby/commit/ce9e9ff4a101eec5632704003fae772e8762eb15
- https://github.com/moby/moby/commit/d32f184696519f909d1db56a060b39f0a08b41c5
- https://github.com/moby/moby/commit/dc56a76bc9f16b2d57b9d64822e305c1e787fcf0
- https://github.com/moby/moby/commit/e5e62b96ce0d4eb3934a386b07203830f55e07ce
- https://github.com/moby/moby/commit/f9705477d023c63fb316a30204761aa1e3cb3e6d

### etcd

- https://github.com/etcd-io/etcd/commit/0b77b42cad99623940c93c5d3b80503de665c198
- https://github.com/etcd-io/etcd/commit/2c83362e63e6b796ea988442483673056c567455
- https://github.com/etcd-io/etcd/commit/2e59635bea6a105581087bb93f68186f35cb0263
- https://github.com/etcd-io/etcd/commit/3ce31acda410db937408ac1c1011fe7b0babd8a7
- https://github.com/etcd-io/etcd/commit/3edd36315d1f57c76deed13b5aacfa6403ff4dc0
- https://github.com/etcd-io/etcd/commit/4bdfc0a46d28f35462a312e1b51a771764321442
- https://github.com/etcd-io/etcd/commit/4d2d2cabb9b0dcaa16ffd17e6d53a745740f3468
- https://github.com/etcd-io/etcd/commit/5d033c22afdf947649b680ed7ad3c1527432ca9e
- https://github.com/etcd-io/etcd/commit/5ee85bea7ca62fe4bf4ab5866ff9862abb42a6bc
- https://github.com/etcd-io/etcd/commit/7adb765660aa7548017583bcb338c5398c7c6fca
- https://github.com/etcd-io/etcd/commit/7f95780bfb5d72c651e870d0cc65c6f2b88700d8
- https://github.com/etcd-io/etcd/commit/91dc6b29a6e000375ba47181db1bfcf8ba92daad
- https://github.com/etcd-io/etcd/commit/b982c80c14d2809534759404703b398fdfdf5d55
- https://github.com/etcd-io/etcd/commit/c678dcbd91721b17d52ef39afb3104444f14deac
- https://github.com/etcd-io/etcd/commit/d7a027e476130efded2005f0b381cd5b283d2978
- https://github.com/etcd-io/etcd/commit/e129223dbebaa5a13b9564dea27fdcd5bbebb317

### grpc-go

- https://github.com/grpc/grpc-go/commit/0be94ab3f591b9b6ba5b3c5702c0701e92b4bc28
- https://github.com/grpc/grpc-go/commit/22c3f92f5faea8db492fb0f5ae4daf0d2752b19e
- https://github.com/grpc/grpc-go/commit/3bf110cd0cef4e896aa6331d44ca4a0c407bbaf3
- https://github.com/grpc/grpc-go/commit/40e7a759a035a36611d6c9a3c2acb11ce1497727
- https://github.com/grpc/grpc-go/commit/46e80bf1f6c2928b216afa3eb9797348c0978ac5
- https://github.com/grpc/grpc-go/commit/7c5299d71e2b8d403195f6071eecea690bf5622a
- https://github.com/grpc/grpc-go/commit/87bcb38fba807cf2f45bc15756795923bd33b4ae
- https://github.com/grpc/grpc-go/commit/9df0e935c037988e64e30498b6ecf3c7a99411a2
- https://github.com/grpc/grpc-go/commit/a62701e4aa1d276bec70311251d62a478404d63f
- https://github.com/grpc/grpc-go/commit/b71aced4a2a1ee80a1cbbd26b85a57623790d7f4
- https://github.com/grpc/grpc-go/commit/c6b46087ab923e9f453ec433f99174cdd45b9b89
- https://github.com/grpc/grpc-go/commit/fa1cb32dc4f81e23ab862dd5e7ac4f2920a33088

### kubernetes

- https://github.com/kubernetes/kubernetes/commit/06082b1bdf4c9ff93e5acf33da49f0b091a47d3e
- https://github.com/kubernetes/kubernetes/commit/0bbb49d2d52675dec586e17763f959634736ac8c
- https://github.com/kubernetes/kubernetes/commit/1f78b0fc6fe497dc2bcee755cc28369756ac41d0
- https://github.com/kubernetes/kubernetes/commit/2e02967acae23126402560a246bafc16d364a52d
- https://github.com/kubernetes/kubernetes/commit/2fd87597a43629ba6aa5d2406dc1737f83e5f6b1
- https://github.com/kubernetes/kubernetes/commit/345f875c51c0acd909f206b855d158b8e3adbbb3
- https://github.com/kubernetes/kubernetes/commit/3c345abafd024853d8ff0fb332db6076cfc610c5
- https://github.com/kubernetes/kubernetes/commit/62055090b491e971bf24b69ef54a83ca0f93b8fd
- https://github.com/kubernetes/kubernetes/commit/647b826d697abdc50aa4808fa21604c9f6fe80a4
- https://github.com/kubernetes/kubernetes/commit/6a624a2b4feebe51cf2acd165e860604fe7f1aba
- https://github.com/kubernetes/kubernetes/commit/6d8f2dddec9b2693fce1488c61fd60e3b2212ded
- https://github.com/kubernetes/kubernetes/commit/79d3d795b512de861c01847fe75c4fc43d2d4f2d
- https://github.com/kubernetes/kubernetes/commit/842f15c3c62a510f3b1718bf1f086b8951533999
- https://github.com/kubernetes/kubernetes/commit/aa808a650585daf17dcbcd13d4d68e7398d4dfd9
- https://github.com/kubernetes/kubernetes/commit/d15de72a92c8841d069b1265e433eb52edc29822
- https://github.com/kubernetes/kubernetes/commit/de1f246e891fd6794185373f3d3722f80e1048d5
- https://github.com/kubernetes/kubernetes/commit/e3311aa93ac6c3ad89d648129fc351aa5eae1e5a
