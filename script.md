{Slide - Hype train}

Evening everyone, my name is Keval and I'm here to tell you why you should try Rust.

{Slide - Funny Rust game screenshot} First off, no, I'm not talking about the game that I'm sure we all know and love, I'm talking about the programming language.

{Slide - Rust logo}

Now, you may be thinking: "What? Another programming language? Aren't there enough of those already?", and to that I'll say: Yes, yes there are... 

{Slide - Megamind}

but Rust is the culmination of all of them.

Alright, alright. Time to back up that big claim with more big claims. I'll paraphrase the [rust-lang.org](https://rust-lang.org) {Slide - Rust site} site; 

"Rust is blazingly fast with no runtime or garbage collector and it guarantees memory and thread safety". 

{Slide - Sweet jesus}{Pause}

They aren't kidding either, Rust stands up to every word and then some.

Have you ever been staring down a C++ bug, talking to your {Slide - Ducks} 8 rubber ducks as if they're your therapist, and, you know, just all around having an existential crisis? {Pause} I'm sure we've all known an equivalent feeling while programming.

Well the way rust works means you never have to deal with _that_ kind of problem again. {Slide - Compiler complains} The compiler literally will not let you make mistakes like that. Rust uses lifetimes and borrowing to ensure all memory you think exists, actually does. Best part is, it does this at compile time so the runtime can still be scarily fast.

Granted all that comes with a few caveats {Slide - Faster Compiler} like the compiler being a bit slow. Or the other small things {Slide - Chaplin} you'll have to deal with in place of your own ignorance.

However, if you ask me, and likely all the people who voted {Slide - StackOverflow} Rust as the most loved language every year since 2016, that is a small price to pay.

Essentially Rust takes C++, removes all the outdated crap, slaps on some sexy syntax and boom. Your favourite parts of CPP and Haskell all together in one place.

Regardless of all that jargon, you should be using Rust just because of {Slide - Cute Ferris} this little guy, his name's Ferris. {Pause} Ferris is a badass, don't let that demeanour fool you.

I'll finish up with a comparison against CPP. {Slide - Code} These are implementations of a Sieve of Eratosthenes. I've tried to make them as comparable as possible but I'm no Rust or CPP god so there's probably far better ways to do things. Good news is, both of these files are on my GitHub so you can make a pull request telling me how stupid I am.

First off, the Rust version straight up runs 24% faster than the CPP one. I got 39,504 nanoseconds for the Rust version and, when it actually ran quickly, CPP gave 49,193 nanoseconds.

Secondly, look at that time code for CPP. I didn't know it was that bad until needing to write this talk!

Then you have the functional-like stuff on the Rust side, I don't know about you but I like the way Haskell works so when functional and procedural are this well integrated, I practically swoon.

I could keep listing things but for the sake of time;

{Slide - Zoot Ferris}

I can't force you to use either language but I hope I've inspired you to, at the very least, try Rust in your next project.

Badass Ferris and I want to thank you for listening.