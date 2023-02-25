### Greetings!!
```C

#include <stdio.h>

typedef struct s_about
{
	char	*name;
	char	*more[4];
	char	*challenge;
}				t_about;

t_about	get_info()
{
	t_about this_me;

	this_me.name	= "Heitor";
	this_me.more[0] = "I like to create games for atari 2600 using Batari.";
	this_me.more[1]= "How to reach me: heitormp@protonmail.com";
	this_me.more[2]= "Fun fact: I started studying at 42 school at age 42, which must mean something... or not!";
	this_me.challenge = "I am currently studying C language at 42 Porto school.";
	return this_me;
}

int	main(int argc, char **argv)
{
	t_about me = get_info();

	printf("Hello, my name is %s!\n", me.name);
	printf("Here is a little more about me:\n")	;
	for (int element = 0; element < 3; element++)
	{
		printf("📌 - %s\n", me.more[element]);
	}
	printf("Challenge: %s", me.challenge);
}
```
### I love talking about programming, games and technology, feel free to contact me!
[leave me a message](https://github.com/HeitorMP/HeitorMP/discussions/1)


<div align="center">
  <a href="https://github.com/HeitorMP">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=HeitorMP&show_icons=true&theme=nord&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HeitorMP&layout=compact&langs_count=7&theme=nord"/>
</div>
