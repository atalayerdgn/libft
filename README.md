
# LIBFT

This project is your very first project as a student at 42. You will need to recode a few functions of the C standard library.





## Example


```C
size_t	ft_strlen(const char *s)
{
	size_t	i;

	i = 0;
	while (s[i] != '\0')
		i++;
	return (i);
}

#include "stdio.h"

int main(void){
	printf("%d\n",strlen("string"));
}
```
## Compile

```bash
  make
  gcc ./libft.a ft_strlen.c
  ./a.out
```

  