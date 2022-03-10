# Image_Processing5

# Space-variant blurring

Assuming the blur to be space-variant, i.e. the standard deviation varies for each pixel. Considering the distribution of sigma to be

sigma(n,m) = A*exp(-((m-N/2)^2 + (n-N/2)^2)) / B) , 0 ≤ m,n ≤ N-1
with sigma(N/2,N/2)=2.0 and sigma(0,0)=0.01.

where N * N is size of the image and pixel indices are in the range [0 , N-1]* [0,N-1]. Finding A and B, and creating the sigma matrix . Gaussian blurring on 'Globe.pgm' using the values of sigma(m,n) was performed.
