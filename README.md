### Greetings!!
```C

#include <stdio.h>

typedef struct s_about
{
	char	*name;
	char	*more[4];
	char	*challange;
}				t_about;

t_about	get_info()
{
	t_about this_me;

	this_me.name	= "Heitor";
	this_me.more[0] = "I like to create games for atari 2600 using Batari.";
	this_me.more[1] = "How to reach me: heitormp@protonmail.com";
	this_me.more[2] = "I like to create games for atari 2600 using Batari.";
	this_me.more[3] = "Fun fact: I started studying at 42 school at age 42, which must mean something... or not!";
	this_me.challange = "I am currently studying programming at 42 Porto school.";
	return this_me;
}

int	main(int argc, char **argv)
{
	t_about me = get_info();

	printf("Hello, my name is %s!\n", me.name);
	printf("Here is a little more about me:\n")	;
	for (int element = 0; element < 5; element++)
	{
		printf("📌 - %s\n", me.more[element]);
	}
	printf("Challange: %s", me.challange);
}
```
<div align="center">
  <a href="https://github.com/HeitorMP">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=HeitorMP&show_icons=true&theme=nord&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HeitorMP&layout=compact&langs_count=7&theme=nord"/>
</div>
