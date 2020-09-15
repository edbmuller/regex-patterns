### Regex patterns

* Match pixels at the end of image filename:

	`(?=300)(\d*[x]\d*)(?=\.(png|jpe?g|gif|webp))/g`

	\> filename-**300x163**.png

* Match pixels at the end of image filename:

	`/(?=300)(\d*[x]\d*)(?=\.(png|jpe?g|gif|webp))/g`

	\> ./assets/imgs/filename-1024x616.png 1024w, ./assets/imgs/filename-768x462.png 768w, **./assets/imgs/filename-300x181.png** 300w, ./assets/imgs/filename.png 1080w

