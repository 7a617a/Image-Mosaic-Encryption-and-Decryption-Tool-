V2.0.0: Enhanced encryption. Each pixel block will not only be rearranged but also undergo different flipping operations after encryption, improving encryption security.
(Note: Encryption/decryption results are incompatible with V1.0.0.)

V2.0.0: 强化加密,每个像素块在加密后除了会重新排列外还会执行不同的翻转处理，提升加密安全性.(注:加密/解密的结果与V1.0.0不兼容).

V2.0.0: 暗号化を強化。各ピクセルブロックは暗号化後、並び替えに加えて異なる反転処理が実行され、暗号化の安全性が向上します。（注：暗号化・復号化の結果は V1.0.0 と互換性がありません。）

# Image-Mosaic-Encryption-and-Decryption-Tool-

This is an image encryption/decryption tool based on HTML + JS, distributed as a single file that requires no installation or runtime environment—simply download it locally and run it directly in a browser.

The tool works by dividing an image into a set number of equally sized pixel blocks, then shuffling these blocks in a specific order determined by a user-defined password before reassembling them into a new image with the same dimensions, aspect ratio, and total pixel count as the original. The block count used for splitting is adjustable; a higher value increases encryption strength. For optimal encryption/decryption results and improved resistance to interference, the chosen block count should ideally divide evenly into both the image's width and height in pixels. 

Unlike conventional encryption tools, the encrypted output remains a valid image file. By using this tool and entering the correct block count and password, the original image can be fully restored. The process is resilient against changes in filename, image format conversion, moderate scaling, and even watermarking. This makes it particularly useful for enhancing the privacy and security of image sharing over the internet—especially on social media platforms that allow free image uploads—effectively protecting against unwanted third-party surveillance or censorship, and safeguarding users' freedom and privacy in information sharing.

Images can be imported either via local upload or through web URLs, with support for batch encryption/decryption, real-time preview of processing, and one-click download of all processed images. Individual files can also be downloaded separately. The interface is simple and efficient, offering language support in Chinese, English, and Japanese. 

Important notice: The author assumes no responsibility or liability for any losses, disputes, legal issues, or consequences arising from your use of this tool, especially those resulting from violations of applicable laws and regulations. Your use of this tool constitutes agreement to these terms; if you do not agree, please refrain from using it.

# 图片马赛克加密解密工具

这是一个图片加密/解密的工具,基于 HTML + JS,单文件,无需安装环境,可直接下载到本地用浏览器来运行.

通过把图片按一定量的像素块数分割成相同大小的若干小块,.根据密码设定的不同将分割后的像素块按序打乱后重新拼接成与原图片尺寸,长宽比,像素数相等的新图片作为加密/解密的方法.(图片分割块数可设定,数值越高,加密强度越大.您设置的分割块数应尽可能的被图片长与宽的像素数整除以提供更好的加密/解密效果,并增强加密图片信息的抗干扰能力.)

不同于普通的加密工具,加密后的图片仍为图片,只需用此工具输入正确的分割的块数与密码与即可解密出原有的图片内容,不受文件名变化,图片格式变化,一定程度的图片缩放及水印标记的影响.用于增加在网络上传播图片信息的隐私与安全性,尤其适合在允许用户免费上传图片内容的各大社交媒体平台上使用,可有效对抗不友善的第三方的窥视与审查,保护用户信息传递的自由与隐私.

可通过本地上传或网络链接的方式导入图片,支持批量加密/解密,过程可实时预览,并支持一键将处理好的图片全部下载到本地.也可单个下载某个所选的文件.操作简单快捷,并提供中文,英文,日文三个语言的版本.

重要信息:您因使用此工具而产生的任何损失,纠纷,争议,及任何因违反法律法规所造成的责任与后果均与此工具的作者无关.当您使用此工具时即代表您同意上述协议,否则请不要使用此工具.

# 画像モザイク暗号化復号化ツール

これは、HTML + JSに基づく画像の暗号化/復号化ツールであり、単一ファイルで構成されており、インストール環境は不要で、直接ダウンロードしてローカルでブラウザで実行できます。

画像を一定数のピクセルブロックに分割し、同じ大きさの複数の小ブロックにし、パスワードの設定に応じて分割後のピクセルブロックを順番に入れ替え、元の画像と同じサイズ、縦横比、ピクセル数の新しい画像を再構成することで暗号化/復号化を行います。（画像の分割ブロック数は設定可能で、数値が高いほど暗号化の強度が高くなります。設定する分割ブロック数は、画像の縦と横のピクセル数でできるだけ整除されるようにすることで、より良い暗号化/復号化効果を提供し、暗号化された画像情報の耐干渉能力を強化します。）

通常の暗号化ツールとは異なり、暗号化後の画像は依然として画像であり、このツールで正しい分割ブロック数とパスワードを入力するだけで、元の画像内容を復号化でき、ファイル名の変更、画像形式の変更、ある程度の画像の拡大縮小、およびウォーターマークの影響を受けません。インターネット上で画像情報を伝播する際のプライバシーとセキュリティを向上させるために使用され、特にユーザーが無料で画像コンテンツをアップロードできる各種ソーシャルメディアプラットフォームで使用するのに適しており、不親切な第三者の盗み見や審査に効果的に対抗し、ユーザーの情報伝達の自由とプライバシーを保護します。

画像はローカルアップロードまたはネットワークリンクでインポートでき、バッチ暗号化/復号化をサポートし、処理中はリアルタイムでプレビューでき、処理済みの画像を一括してローカルにダウンロードすることも、選択したファイルを単独でダウンロードすることもできます。操作は簡単で迅速で、中国語、英語、日本語の3つの言語バージョンを提供しています。

重要な情報：このツールの使用によって生じたいかなる損失、紛争、争議、および法律法規に違反することによる責任と結果は、このツールの作者とは一切関係ありません。このツールを使用することで、上記の協定に同意したことになります。同意しない場合は、このツールを使用しないでください。
