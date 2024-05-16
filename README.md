# rust-file-compressor

A high-performance file compression tool written in Rust. This utility offers efficient and reliable methods for compressing and decompressing files, utilizing Rust's speed and safety features. Ideal for developers and users looking for a robust solution to manage file sizes.

## Features

- Fast and efficient compression and decompression
- Support for various file formats
- Easy-to-use command-line interface
- Safe and secure handling of files

## Installation

To install rust-file-compressor, you need to have [Rust](https://www.rust-lang.org/) installed. You can then build the project using Cargo:

```sh
git clone https://github.com/Quinos2003/rust-file-compressor.git
cd rust-file-compressor
cargo build --release
```

## Usage

After building the project, you can use the `rust-file-compressor` binary to compress and decompress files. 

### Compress a file

```sh
./target/release/rust-file-compressor compress <input_file> <output_file>
```

### Decompress a file

```sh
./target/release/rust-file-compressor decompress <input_file> <output_file>
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request on GitHub.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
