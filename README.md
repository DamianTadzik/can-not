# CAN NOT

## Description
This is library/wrapper for CAN peripherial. It is based on FreeRTOS and HAL. It is meant to be reliable and user friendly. Naming convention "can not" "cant" is used to distinguish that this is different implementation from "can" libraries used previously. 

## SuperDescription
API consist of four C functions, usage is described inside header file:
- `cant_main_init()` 
- `cant_freertos_init()`
- `cant_transmit()`
- `cant_receive()`
User also should provide define of can instance used, and for now has only three options:
- STM32F446RE `CANT1` or `CANT2` 
- STM32Fxxxx `CAN`
There are debug counters implemented in source file, and they are available after defining:
- `CANT_DEBUG` 

## Created by
Damian Brzana aka @DamianTadzik on github aka @DamianTadziu on gitlab - 2024
