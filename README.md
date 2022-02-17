Below you can find colors reference of text to command when running node.js application:

``console.log('\x1b[36m%s\x1b[0m', 'I am cyan');  //cyan``

``console.log('\x1b[33m%s\x1b[0m', stringToMakeYellow);  //yellow``

Note %s is where in the string (the second argument) gets injected. \x1b[0m resets the terminal color so it doesn't continue to be the chosen color anymore after this point.

Colors reference

``const x=[0,1,2,3,4,5,6,7,8,9,21,30,31,32,33,34,35,36,40,41,42,43,44,45,46,47,52,90,91,92,93,94,95,96,97,98,99,100,101,102,103,104,105,106]``

``for (let i = 0; i < x.length; i++)``

``console.log(`Code(x1b[${x[i]}) ==> \x1b[${x[i]}m Hello From Consol \x1b[0m`)``

![img](https://github.com/amr88nzzal/color_your_console/blob/main/colors.jpg)

