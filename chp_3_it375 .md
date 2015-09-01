# Chapter 3 - The Physical Layer

##  Data and Signals

### Analog and Digital

**Analog data**, such as the sounds made by a human voice, take on continuous values. When someone speaks, an analog wave is created in the air. This can be captured by a microphone and converted to an analog signal or sampled and converted to a digital signal.

**Digital data** take on discrete values. For example, data are stored in computer memory in the form of 0s and 1s. They can be converted to a digital signal or modu- lated into an analog signal for transmission across a medium.

### Periodic Analog Signals

Periodic analog signals can be classified as simple or composite. A simple periodic analog signal, a **sine wave**, cannot be decomposed into simpler signals. A composite periodic analog signal is composed of multiple sine waves.

#### Amplitude

The peak amplitude of a signal is the absolute value of its highest intensity, propor- tional to the energy it carries. For electric signals, peak amplitude is normally measured in volts.

![Peak Amplitude](./img/ch3-amp)

#### Period and frequency

**Period** refers to the amount of time, in seconds, a signal needs to complete 1 cycle. **Frequency** refers to the number of periods in 1 s. Note that period and frequency are just one characteristic defined in two ways. Period is the inverse of frequency, and frequency is the inverse of period, as the following formulas show.

	ƒ=1/T   and    T=1/ƒ

The units of period and frequency are detailed in the following table.

![Peak Amplitude](./img/ch3-units-period-freq)

### Phase

The **phase** of an oscillation or wave refers to a sinusoidal function such as the following:

:<math>\begin{align}
x(t) &= A\cdot \cos( 2 \pi f t + \varphi ) \\
y(t) &= A\cdot \sin( 2 \pi f t + \varphi ) = A\cdot \cos\left( 2 \pi f t + \varphi - \tfrac{\pi}{2}\right)
\end{align}</math>

where <math>\scriptstyle A\,</math>, <math>\scriptstyle f\,</math>, and <math>\scriptstyle \varphi\,</math> are constant parameters called the ''amplitude'', ''frequency'', and ''phase'' of the sinusoid.  These functions are periodic with period <math>\scriptstyle T = \frac{1}{f}\,</math>, and they are identical except for a displacement of <math>\scriptstyle \frac{T}{4}\,</math> along the <math>\scriptstyle t\,</math> axis.

#### Wavelength

**Wavelength** is another characteristic of a signal traveling through a transmission medium. Wavelength binds the period or the frequency of a simple sine wave to the propagation speed of the medium. Wavelength is the distance
