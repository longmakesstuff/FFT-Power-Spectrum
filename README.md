# FFT power spectrum visualizer

A high-quality demonstration of the application can be found at
- https://www.youtube.com/watch?v=AaJ25F8pjOw
- https://www.youtube.com/watch?v=HsuVb4TDCqU

![](data/output-opt.gif)

### Build and run (C++11 / SFML 2.5)

Install the dependencies

```
sudo apt-get install libsfml-dev
```

Clone the repository

```
git clone https://github.com/longmakesstuff/FFT-Power-Spectrum.git --depth 1
```

Compile

```
cd FFT-Power-Spectrum
mkdir build
cd build
cmake ..
make -j8
```

And play any `WAV` file with 

```
./bin/main [song-path.wav]
```

### References
- Louisa Renz's bachelor thesis - University Tübingen
- [RosettaCode's Cooley-Tukey FFT](https://rosettacode.org/wiki/Fast_Fourier_transform)
- [Hann's function](https://en.wikipedia.org/wiki/Hann_function)
- [Fourier transform for dummies](https://math.stackexchange.com/questions/1002/fourier-transform-for-dummies)
