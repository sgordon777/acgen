AC generator, 2-phase, 3-phase, or 4-phase


project/
 ├── src/        user code (compiled)
 ├── include/    user headers
 ├── lib/        reusable libs
 ├── platformio.ini
 ├── Src/           dropped from CubeMx
 ├── Inc/           dropped from CubeMx


GPIO
PA5		out
PB4		out
PB13	out
PB14	out
PC3		out     en
PC12	in
PC13	in		button

Timer
PC0		out		timer1_ch1p A+
PA7		out		timer1_ch1n A-
PC1		out		timer1_ch2p B+
PB0		out		timer1_ch2n B-
PC2		out		timer1_ch3p C+
PB15	out		timer1_ch3n C-
PA15	out		timer2_ch1  ENCA
PA1		out		timer2_ch2  ENCB

Adc
PA0		in		ADC_IN1     A
PB12	in 		ADC1_IN11   C
PB11  	in 		ADC1_IN14   ref
PB1		in		ADC1_IN2    B

SPI
PC10	out		SPI_CLK
PC11	in 		MISO
PB5  	out		MOSI