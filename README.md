# Media Player Classic History

神级播放器Media Player Classic(MPC)已经死亡，MPC-HC也停止了更新维护，作为多媒体播放得擎天柱项目之一，盛名在外却也难免终结。但是历史将铭记MPC的光辉，让我们向MPC/MPC-HC及他们的开发者们致敬。



# MPC的前世今生

MPC全称Media Player Classic，是一个和Windows Media Player有密切关系的开源作品。

微软在2000年推出了新版的Windows Media Player 7.0，易用性及体验引起用户不满，开发者们推出了其异构版本-MPC于2003年诞生。



MPC的功能要比Windows Media Player更加强大，而且还是开源的，只要遵循GPL条款，任何人都可以为MPC的发展贡献出自己的力量。MPC日益壮大，业界越来越多人把目光聚集在这款看似经典、但又无比先进的播放器身上。



MPC支持的格式非常全面，在2005年MPC就已经可以通杀VCD、SVCD、DVD等光盘的播放，而且还支持AC3、AAC、DTS音频解码。最重要的是，MPC对当时被视为未来的视频编码H.264/AVC提供了完善的支持——在今天，H.264/AVC已经成为绝对的主流。MPC在十多年前就已经拥有解码当今视频的能力，其先进程度由此可见一斑。



于是，不愉快的事情发生了——在2005年MPC的代码遭到了盗窃，有商业性质的视频播放器非法使用了MPC的开源代码，导致了MPC项目发起人Gabest的淡出，MPC开发一度停滞。不过在2006年，新的开发者接管了MPC的项目，以MPC为基础开发了MPC-HC，这一大神级别的播放器得以续命。



# MPC的兴衰之路



MPC的播放能力之所以如此强，和它架构是有关系的。

MPC使用的是DirectShow架构，在这个架构之中，MPC可以通过Win系统提供的DirectShow接口，来调用各种解码器。例如，MPC能够封装ffdshow等DirectShow滤镜，从而获得强有力的解码能力。在MPC-HC中，MPC的滤镜得到了进一步的发展，支持MPC-HC的外挂滤镜层出不穷，最后，神级滤镜LAV的出现，让MPC的视频解码近乎无敌。



LAV是一个基于FFmpeg的滤镜，无论是分离器还是解码器，表现都无与伦比。LAV滤镜提供了强大的GPU硬解能力，而且支持10bit、H.265/HEVC等先进视频技术的解码。在2013年，MPC-HC全面拥抱LAV滤镜，这令MPC-HC的视频解码能力继续领跑业界。



**除了本质的视频解码，MPC-HC的其他功能也在开发者们的贡献下逐步完善。例如Underground78这位开发者为MPC-HC贡献了新的字幕渲染器和toolbar，alexmarsev贡献了新的音频解码器，Attila Tamás Áfra贡献了色彩管理等等。众人拾柴火焰高，MPC-HC的功能越来越接近无可挑剔，但与此同时，开发者们向MPC-HC递交代码的速度一再放缓。**



虽然MPC-HC是各个开发者共同努力的结晶，但这些开发者们的相处并不顺利，MPC项目也多次更换主导者。MPC的发起人是Gabest，但受到源代码被盗用的打击，Gabest慢慢淡出了MPC的开源项目。随后Casimir666接过了手，开发出了后续版本MPC-HC，一段时间后Casimir666也开始淡出，Aleksoid和Xhmikosr这两位开发者成为了主力。

在2012年，Aleksoid和Xhmikosr发生了争执，直接的后果就是Aleksoid离开了MPC-HC项目，另起炉灶建立起了另一分支MPC-BE。MPC-HC的开发者逐渐减少，现在，Xhmikosr终于宣布，MPC-HC停止开发，项目再也无人维护。



MPC-HC的功能已经非常完善，就算不再更新，它也可以满足未来相当长时间内的视频播放需求。但MPC-HC是不是真的已经改无可改？也未必，起码它对触控的支持就挺糟糕。但是，MPC-HC的出发点毕竟是保持WMP 6.4的作风，在WMP 6.4的界面框架下，MPC-HC可以说已经做到了极致。这个同人作品现在终于走向落幕，11年间风雨飘摇的开发历程，足以令人脱帽致敬。



# MPC的掘墓人



MPC/MPC-HC是遵循GPL条款的开源软件，如果其他软件使用了相应代码，那么该软件也必须开源。但并不是所有人都尊重开源协议的，不少播放器直接拿了MPC/MPC-HC的代码使用，但就是不开源，这毫无疑问属于抄袭行为。

**KMPlayer**：这是大家都相当熟悉的播放器。KMPlayer来自韩国开发者勇囍，这款播放器在2005年盗窃了MPC的代码。MPC的开创者Gabest对此无所适从，大受打击，随后退出了MPC项目。现在KMPlayer躺在FFmpeg的耻辱名单上。

**PotPlayer**：这也是大家很熟悉的播放器。它是KMPlayer作者勇囍2008进入Daum公司后的作品，同样盗用了MPC的代码。和KMPlayer一样，PotPlayer也躺在FFmpeg的耻辱名单上。



**暴风影音**：暴风影音起初能火，是因为它几乎可以解码所有的音频视频，非常万能。但这本质上是靠MPC以及捆绑其他一大推外挂解码器来实现的。后脱离MPC，但在2009年被举报仍在使用GPL代码，被加入了FFmpeg的耻辱名单。



**QQ影音**：被很多人誉为腾讯的良心，但在2009年，它和暴风影音一同被加入了FFmpeg耻辱名单，它现在依然在使用源自MPC的Gabest分离器。



# MPC的未来

MPC-HC是一个值得尊敬的开源软件，它树立了基于DirectShow的视频解码体系，是很多视频播放器的灵感所在。MPC-HC已经向我们告别，但好消息还是有的！著名解码包K-Lite Codec Pack一直捆绑有MPC-HC，K-Lite Codec Pack已经表态，将会继续维护包含在MPC-HC的解码组件，MPC-HC的解码器应该还会持续进化。

K-Lite将会继续维护MPC-HC的解码包，管理员称MPC-HC本来就半死不活，解码包才是最重要的。

最后，让我们再次向MPC致敬，期待MPC能够浴火重生，凤凰涅槃。