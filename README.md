# deno-playground

📚 Learning and exploring Deno.

> A modern runtime for JavaScript and TypeScript.
> 
> -- <cite>https://deno.land/</cite>


## Description

In [episode #443](https://changelog.com/podcast/443) on one of the best software podcasts, [The Changelog](https://changelog.com/),
Ryan Dahl described his next big thing: Deno. It's an articulate, information-dense podcast episode and I recommend it.

I know JavaScript and npm and now I want to learn TypeScript. It seems like a good time to learn Deno at the same time!
This project is me doing that.


## Instructions

Follow these instructions.

1. Pre-requisite: Deno
   * I used Deno `1.31.1` for this project.
   * I manage my Deno installation with HomeBrew (although the options are great too).
2. Run the program:
   * ```shell
     deno run --allow-net webserver.ts
     ```
3. Open the browser
   * Open the browser at <http://localhost:8000/> and see a message!


## Notes

I'm using Intellij IDEA to work on this project (as I do for most projects). I have the official Deno plugin installed.


## Wish List

General clean ups, todos and things I wish to implement for this project:

* [ ] Consider making multiple subprojects. I always like a `basic` project that highlights a minimal feasible example
  and I try to keep it idiomatic instead of unrealistically over-simplified. By contrast, then I like various
  intermediate examples showcasing more examples. Specifically, I want Deno projects that use import maps, import npm
  modules (a big change in Deno's philosophy!), and a bundled project.


## Reference

* [Deno](https://deno.land/)
