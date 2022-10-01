# 2022_09_30
"Eat Your Own Catfood."

#### 何をダウンロードすればいいのニャ？


	GitHub では日付でリリースが管理されているニャ

		+ プロジェクト内部では 10/20/30 日に中間リリースしているニャ
		+ そのうち 30 日のリリースを GitHub で公開しているニャ

		最新版のページを開いて ZIP の項目をクリックするニャ
		画面が遷移したら "Download" を選ぶニャ
		どこにダウンロードされるかはブラウザや Windows によって違うニャ

	セキュリティの解除方法

		Windows
			ZIP ファイルのプロパティから解除するニャ

		Mac
			サンドボックスを調整するニャ




	[ nonnon_win_ansi.zip ]

		ANSI (A) 版と呼ばれる Win9x (95/98/Me) で実行できるものだニャ
		NT の系列でも実行できるのニャがシステム言語しか扱えないニャ

		メモリが３ＧＢまでしか扱えないニャ

		+ MinGW GCC によって作成されているニャ

	[ nonnon_win_unicode.zip ]

		Unicode (W) 版で Win9x では実行できないニャ
		WinNT(NT4/2000/XP/Vista/7/8/8.1/10) で実行できるニャ
		64-bit 版でも実行できるニャ

		メモリが３ＧＢまでしか扱えないニャ

		+ MinGW GCC によって作成されているニャ

	[ nonnon_win_x64.zip ]

		64-bit 版で 64-bit 版 Windows で実行できるニャ
		32-bit OS では実行できないニャ

		メモリが３ＧＢ以上扱えるニャ

		+ Visual C++ で作成されているニャ

	[ project_nonnon.zip ]

		ソースコードでニャ
		アイコンやサウンドといったリソースも入っているニャ

		バッチファイルを使っているので簡単にコンパイルできるニャ
		NonnonApps や GameConsole でなく単体の EXE が欲しい時にも使えるニャ




	[ Nonnon for Mac ]

		Mac 移植版だニャ
		Win32 版とはいくらか違った実装になっているニャ

		以下のアプリがあるニャ

			CatPad
			hunyapiyo3
			Marie
			Freecell
			Nonnon Paint
			Pinknoise
			Project Checker

		今の所 Mac mini Late 2012 / Catalina では動くニャ

	[ Nonnon for Mac Source ]

		Nonnon for Mac のプロジェクトになるニャ
		Xcode で開けると思うニャ
