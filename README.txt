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


hookup to amp board

        NUCLEO                      8302
        PIN         FUNC            PIN     FUNC
PWM_A   CN7-38      TIM1_1_PC0      11      INH-A
PWM_B   CN7-36      TIM1_2_PC1      13      INH-B
PWM_C   CN7-35      TIM2_3_PC2      15      INH-C
EN      CN7-37      GPIO_PC3        10      EN
SO1     CN7-28      ADC1_CH0_PA0    22      SO1
SO2     CN7-32      ADC2_CH17_PA4   21      SO2
REF     CN7-34      ADC1_CH15_PB0   32      REF-1.65V
ENCA    CN7-17      TIM2_CH1_PA15 
ENCB    CN7-30      TIM2_CH2_PA1


