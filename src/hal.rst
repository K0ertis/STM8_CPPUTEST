                                      1 ;--------------------------------------------------------
                                      2 ; File Created by SDCC : free open source ANSI-C Compiler
                                      3 ; Version 3.6.0 #9615 (Linux)
                                      4 ;--------------------------------------------------------
                                      5 	.module hal
                                      6 	.optsdcc -mstm8
                                      7 	
                                      8 ;--------------------------------------------------------
                                      9 ; Public variables in this module
                                     10 ;--------------------------------------------------------
                                     11 	.globl _uart_init
                                     12 ;--------------------------------------------------------
                                     13 ; ram data
                                     14 ;--------------------------------------------------------
                                     15 	.area DATA
                                     16 ;--------------------------------------------------------
                                     17 ; ram data
                                     18 ;--------------------------------------------------------
                                     19 	.area INITIALIZED
                                     20 ;--------------------------------------------------------
                                     21 ; absolute external ram data
                                     22 ;--------------------------------------------------------
                                     23 	.area DABS (ABS)
                                     24 ;--------------------------------------------------------
                                     25 ; global & static initialisations
                                     26 ;--------------------------------------------------------
                                     27 	.area HOME
                                     28 	.area GSINIT
                                     29 	.area GSFINAL
                                     30 	.area GSINIT
                                     31 ;--------------------------------------------------------
                                     32 ; Home
                                     33 ;--------------------------------------------------------
                                     34 	.area HOME
                                     35 	.area HOME
                                     36 ;--------------------------------------------------------
                                     37 ; code
                                     38 ;--------------------------------------------------------
                                     39 	.area CODE
                                     40 ;	src/hal.c: 13: void uart_init(void){
                                     41 ;	-----------------------------------------
                                     42 ;	 function uart_init
                                     43 ;	-----------------------------------------
      0080AD                         44 _uart_init:
                                     45 ;	src/hal.c: 17: }
      0080AD 81               [ 4]   46 	ret
                                     47 	.area CODE
                                     48 	.area INITIALIZER
                                     49 	.area CABS (ABS)
