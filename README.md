

# Stagg: Static Site Generator in Go 🚀

Stagg is a blazing-fast, fully asynchronous static site generator written in pure Go, leveraging only the Go standard library. Designed for simplicity, extensibility, and speed, Stagg empowers users to build and deploy beautiful static websites with ease—perfect for hosting on GitHub Pages. 🌐


## ✨ Features

- 🛡️ **No External Dependencies:** Built entirely with Go's stdlib for maximum portability and reliability.
- 🏁 **GitHub Pages Ready:** Output is fully compatible for direct deployment to GitHub Pages.
- 🧑‍💻 **Easy to Use:** Simple CLI and clear terminology for effortless site generation.
- 🧩 **Extensible:** Supports custom extensions to add new features and functionality.
- 🎨 **Customizable:** Modify site appearance with templates and CSS for complete control over design.
- ⚡ **High Performance:** Asynchronous, multi-threaded architecture for fast rendering and generation.
- 🆓 **Open Source:** Free for everyone to use, contribute, and enjoy.


## 🚦 Getting Started

1. 🛠️ **Install Go:** Make sure you have Go installed ([download here](https://golang.org/dl/)).
2. 📦 **Clone the Repository:**
	```sh
	git clone https://github.com/biplobmanna/stagg.git
	cd stagg
	```
3. 🧹 **Initialize the Project:**
	```sh
	go mod tidy
	```
4. 🏗️ **Build the Generator:**
	```sh
	go build -o stagg
	```
5. 🏃 **Generate Your Site:**
	```sh
	./stagg generate
	```


## 📚 Terminology

- 📂 **Source Directory:** Where your markdown/content files live.
- 🗂️ **Templates:** HTML files that define the structure of your site.
- 🧩 **Extensions:** Go plugins or scripts to extend generator functionality.
- 🖼️ **Assets:** CSS, images, and other static files.
- 📤 **Output Directory:** Where the generated site is written.


## 🛠️ Customization

- 🗂️ **Templates:** Easily swap or edit HTML templates for custom layouts.
- 🎨 **CSS:** Add or modify stylesheets for unique designs.
- 🧩 **Extensions:** Write Go code to add new features—see the `extensions/` folder for examples.


## ⚡ Performance

Stagg uses Go's goroutines and channels to parallelize rendering and generation, making it extremely fast even for large sites. 🏎️


## 🤝 Contributing

Contributions are welcome! Please fork the repo, create a feature branch, and submit a pull request. All ideas, bug fixes, and improvements are appreciated. 🙏


## 📄 License

Stagg is released under the MIT License. See [LICENSE](LICENSE) for details.


## 🎉 Enjoy!

Stagg is free for all to use, contribute, and enjoy. Build your next static site with speed and simplicity! ✨
