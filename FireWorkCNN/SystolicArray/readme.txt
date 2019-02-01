Systolic Array

	 x11 x12 x13 
X =  x21 x22 x23
     x31 x32 x33

	 w11 w12 w13
W =  w21 w22 w23
     w31 w32 w33

////==== Result 

    	xw11 xw12 xw13
X*W =	xw21 xw22 xw23
		xw31 xw32 xw33


xw11 = x11*x11 + x12*w21 + x13*w31

xw12 = x11*w12 + x12*w22 + x13*w32

xw13 = x11*w13 + x12*w23 + x13*w33

xw21 = x21*w11 + x22*w21 + x23*w31

xw22 = x21*w12 + x22*w22 + x23*w32

xw23 = x21*w13 + x22*w23 + x23*w33

xw31 = x31*w11 + x32*w21 + x33*w31

xw32 = x31*w12 + x32*w22 + x33*w32

xw33 = x31*w13 + x32*w23 + x33*w33

