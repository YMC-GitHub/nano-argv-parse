a library package for parsing command-line style parameters

## background

why develop such a library package? Does it have any value?

in the process of development coding, some command tools are often written to assist development. There have been several tools written in a short period of time, with similar architectures, but different business logics. For better multiplexing, common parts need to be extracted.

There was a need: The backend has developed an interface, and the frontend needs to directly reuse the code if backend interface.

I don't know if it's right or wrong to equate value with money simply and crudely, but if you lose your foundation, everything will be nothing but a castle in the air.


What do people often say about opportunity? I think it is: a person in the accumulation of knowledge, learning skills at the same time, good at using the development of vision to observe this fast-changing world, when you have the ability to solve a problem, it is an opportunity for you.

## features

- Parsing command-line style parameters
- Support text input and JS array input

## User installing

- You can import directly via npm cdn
```html
<!-- unpkg.com/:package@:version/:file -->
<!-- unpkg.com/nano-argv-parse@1.0.0/dist/main.js -->
<!-- jsdelivr -->
<!-- unpkg.zhimg.com -->
```

- You can install it via the npm library tool
```bash
npm i nano-argv-parse
```

```bash
yarn add nano-argv-parse
```

```bash
pnpm add nano-argv-parse
```


## Product Closed Loop

Small, single function, only do one thing-parse command-line style parameters

## Product operation and maintenance

Because the function is simple, it determines its development speed, update speed, problem speed will not be slow

## product plans

Because the function is single, the function has been basically completed. In the later stage, small patches will be updated mainly according to the needs of command packages or other class libraries. There will be no major changes in functions. The architecture may change with the update of technology.


A command tool for editing json files in the command line interface will be open sourced later using such a library package

## license certificate

You can do anything with it, but please do not violate the laws of your area. I will not accept any responsibility for your actions.


## concluding remarks

> I am proud to be a programmer, and although I don't leave home, I have the power to change the world (maybe a little big) at my fingertips. Even if it can't be achieved, it's a good goal to strive for. -- from lencx

It is a blank sheet of paper, you have any ideas, you can directly code out, how to compile, how to set the rules, you decide.

