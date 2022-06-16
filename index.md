# Miley Cyrus pic below

![Image of my beloved Miley Cyrus](https://upload.wikimedia.org/wikipedia/commons/thumb/5/52/Miley_Cyrus_Primavera19_-226_%2848986293772%29_%28cropped%29.jpg/640px-Miley_Cyrus_Primavera19_-226_%2848986293772%29_%28cropped%29.jpg)

## Code Example

```
unsigned long	calculate_ms(struct timeval time_base, struct timeval time_now)
{
	return (time_now.tv_sec * 1000 + time_now.tv_usec / 1000
		- time_base.tv_sec * 1000 - time_base.tv_usec / 1000);
}
```
