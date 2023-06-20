# divnet-rs

[DivNet](https://github.com/adw96/DivNet) is an R package for estimating diversity when taxa in the community co-occur via ecological networks. It leverages information from multiple samples and data about the samples (covariates) in order to give more accurate estimates of variance in the measured diversity. Possibly it's coolest feature is that, unlike most existing methods of measuring diversity, it uses models from [compositional data analysis](https://en.wikipedia.org/wiki/Compositional_data) that take into account ecological networks in which taxa positively and negatively co-occur.

While the DivNet R package makes it simple to apply the algorithms from [Willis & Martin 2020](https://github.com/adw96/DivNet) to your data, it does have trouble with large datasets. This is where `divnet-rs` comes it. It is a [Rust](TODO) implementation of the DivNet algorithm. It allows you to successfully run much larger datasets even on your laptop!

In this book, you will find documentation and information for installing and using `divnet-rs`. Additionally, I will go over a couple examples and a tutorial to help you get started!

For more background information and the theory behind DivNet, please check out the [original DivNet repository](https://github.com/adw96/DivNet) and the [DivNet manuscript](https://doi.org/10.1093/biostatistics/kxaa015).

You can find the `divnet-rs` source code on [GitHub](https://github.com/mooreryan/divnet-rs).

## License

 <p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/mooreryan/divnet-rs-book">divnet-rs book</a> by <span property="cc:attributionName">Ryan M. Moore</span> is licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"></a></p>
