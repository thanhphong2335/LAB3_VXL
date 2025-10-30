/*
 * timer.c
 *
 *  Created on: Oct 29, 2025
 *      Author: Thanh Phong
 */

 #include "main.h"
 #include "input_reading.h"
 void HAL_TIM_PeriodElapsedCallback(TIM_HandleTypeDef *htim)
 {
	 if(htim->Instance == TIM2){
		 button_reading();
	 }
 }
