### Regex patterns

* Match pixels at the end of image file name:

	`(?=300)(\d*[x]\d*)(?=\.(png|jpe?g|gif|webp))/g`

	file-name-**300x163**.png