

Sometimes, after saving this driver, Hubitat changes some characters that we don't want changing!
 
		& # 1 7 6 ; F = degrees F

          	W / m & # 1 7 8 ; = W/m�

          If on lines 246 and 242 you see W/m� then you need to change it to: W/m & # 1 7 8 ; (without any spaces in between characters)

          If on lines 258, 288, 312 & 324 you see �F then you need to change it to: & # 1 7 6 ; F (without any spaces in between characters)