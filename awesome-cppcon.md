
## CppCon 2016

- [(official) slide collections](https://github.com/CppCon/CppCon2016)
- [(official) video collections](https://www.youtube.com/playlist?list=PLHTh1InhhwT7J5jl4vAhO1WvGHUUFgUQH)

## Gu Lu's Picked List

- :star: 'must-reads' in this list (8 out of 18).

Tags | Category | Title | Note
-------- | -------- | ----- | ----
 | Tutorial | [**A \<chrono\> Tutorial**][chrono] by Howard Hinnant ([video][chrono_video]) | [`std::chrono` Reference][chrono_ref]
 | Tutorial | [**tuple, What's New, And How It Works**][tuple] by Stephan T. Lavavej ([video][tuple_video]) | [`std::tuple` Reference][tuple_ref]
 | Tutorial | [**Variants - Past, Present, and Future**][variant] by David Sankel ([video][variant_video]) | [`std::variant` Reference][variant_ref]
:star: | Tutorial | [**accumulate - Exploring an Algorithmic Empire**][accumulate] by Ben Deane ([video][accumulate_video]) | 
:star: | Tutorial | [**Variadic expansion in examples**][variadic] by Michał Dominiak ([video][variadic_video]) | 
 | Library | [**BDE Libraries - An Orientation**][bde] by Steven Breitstein ([video][bde_video]) | [BDE Wiki][bde_ref]
 | Library | [**The Blaze High Performance Math Library**][blaze] by Klaus Iglberger ([video][blaze_video]) | [repo][blaze_repo]
:star: | Tool | [**Conan - C and C++ package manager**][conan] by Diego Rodriguez-Losada ([video][conan_video]) | [conan.io][conan_io]
:star: | Tool | [**uftrace - A function graph tracer C C++ userspace programs**][uftrace] by Namhyung Kim and Honggyu Kim ([video][uftrace_video]) | [GitHub Repo][uftrace_repo]
 | Practice | [**Out of memory - Business as usual**][oom] by Sergey Zubkov (video: N/A) | 
 | Practice | [**The Exception Situation**][exception] by Patrice Roy ([video][exception_video]) | 
:star: | Practice | [**What is the basic interface**][interface] by Lisa Lippincott (video [part1][interface_video1] [part2][interface_video2]) | 
:star: | Practice/Opt | [**Practical Performance Practices**][p_perf] by Jason Turner ([video][p_perf_video]) | 
 | Concurrency | [**The Continuing Future of Concurrency in C++**][concurrency] by Anthony Williams ([video][concurrency_video]) | 
 | Heterogeneous | [**Towards Heterogeneous Programming in C++**][heterogeneous] by Gordon Brown and Michael Wong ([video][heterogeneous_video]) | 
:star: | GameDev | [**Game Engine Using C++11**][game_engine] by Jason Jurecka(Blizzard) ([video][game_engine_video]) | 
:star: | GameDev/Opt | [**Rainbow Six Siege - Quest for Performance**][r6] by Nicolas Fleury ([video][r6_video]) | 
 | General | [**The Evolution of C++ - Past, Present, and Future**][bj] by Bjarne Stroustrup ([video][bj_video]) | 

- Pull-requests are welcome. 
- Prefer lightweight facilities to heavyweight libraries/frameworks (like boost/qt/etc.).
- Prefer immediately adoptable practices to underground theoretical implementation details.

[chrono]: https://github.com/CppCon/CppCon2016/blob/master/Tutorials/A%20chrono%20Tutorial/A%20chrono%20Tutorial%20-%20Howard%20Hinnant%20-%20CppCon%202016.pdf
[chrono_video]: https://www.youtube.com/watch?v=P32hvk8b13M
[chrono_ref]: http://en.cppreference.com/w/cpp/chrono

[interface]: https://github.com/CppCon/CppCon2016/blob/master/Presentations/What%20is%20the%20basic%20interface/What%20is%20the%20basic%20interface%20-%20Lisa%20Lippincott%20-%20CppCon%202016.pdf
[interface_video1]: https://www.youtube.com/watch?v=s70b2P3A3lg&index=56&list=PLHTh1InhhwT7J5jl4vAhO1WvGHUUFgUQH
[interface_video2]: https://www.youtube.com/watch?v=Uzu5CuGfmGA&index=55&list=PLHTh1InhhwT7J5jl4vAhO1WvGHUUFgUQH

[tuple]: https://github.com/CppCon/CppCon2016/blob/master/Presentations/tuple,%20What's%20New,%20And%20How%20It%20Works/tuple,%20What's%20New,%20And%20How%20It%20Works%20-%20Stephan%20T.%20Lavavej%20-%20CppCon%202016.pdf
[tuple_video]: https://www.youtube.com/watch?v=JhgWFYfdIho&index=76&list=PLHTh1InhhwT7J5jl4vAhO1WvGHUUFgUQH
[tuple_ref]: http://en.cppreference.com/w/cpp/utility/tuple

[variant]: https://github.com/CppCon/CppCon2016/blob/master/Presentations/Variants%20-%20Past,%20Present,%20and%20Future/Variants%20-%20Past,%20Present,%20and%20Future%20-%20David%20Sankel%20-%20CppCon%202016.pdf
[variant_video]: https://www.youtube.com/watch?v=k3O4EKX4z1c&index=33&list=PLHTh1InhhwT7J5jl4vAhO1WvGHUUFgUQH
[variant_ref]: http://en.cppreference.com/w/cpp/utility/variant

[variadic]: https://github.com/CppCon/CppCon2016/blob/master/Presentations/Variadic%20expansion%20in%20examples/Variadic%20expansion%20in%20examples%20-%20Micha%C5%82%20Dominiak%20-%20CppCon%202016.pdf
[variadic_video]: https://www.youtube.com/watch?v=Os5YLB5D2BU&index=47&list=PLHTh1InhhwT7J5jl4vAhO1WvGHUUFgUQH

[bde]: https://github.com/CppCon/CppCon2016/blob/master/Tutorials/BDE%20Libraries%20-%20An%20Orientation/BDE%20Libraries%20-%20An%20Orientation%20-%20Steven%20Breitstein%20-%20CppCon%202016.pdf
[bde_video]: https://www.youtube.com/watch?v=Iess36CZnPI
[bde_ref]: https://github.com/bloomberg/bde/wiki

[p_perf]: https://github.com/CppCon/CppCon2016/blob/master/Tutorials/Practical%20Performance%20Practices/Practical%20Performance%20Practices%20-%20Jason%20Turner%20-%20CppCon%202016.pdf
[p_perf_video]: https://www.youtube.com/watch?v=uzF4u9KgUWI

[bj]: https://github.com/CppCon/CppCon2016/blob/master/Keynotes/The%20Evolution%20of%20C++%20-%20Past,%20Present,%20and%20Future/The%20Evolution%20of%20C++%20-%20Past,%20Present,%20and%20Future%20-%20Bjarne%20Stroustrup%20-%20CppCon%202016.pdf
[bj_video]: https://www.youtube.com/watch?v=_wzc7a3McOs

[blaze]: https://github.com/CppCon/CppCon2016/blob/master/Tutorials/The%20Blaze%20High%20Performance%20Math%20Library/The%20Blaze%20High%20Performance%20Math%20Library%20-%20Klaus%20Iglberger%20-%20CppCon%202016.pdf
[blaze_video]: https://www.youtube.com/watch?v=w-Y22KrMgFE
[blaze_repo]: https://bitbucket.org/blaze-lib/blaze

[conan]: https://github.com/CppCon/CppCon2016/blob/master/Demos/Conan%20C%20and%20C++%20package%20manager/Conan%20C%20and%20C++%20package%20manager%20-%20Diego%20Rodriguez-Losada%20-%20CppCon%202016.pdf
[conan_video]: https://www.youtube.com/watch?v=xvqH_ck-5Q8
[conan_io]: https://conan.io/

[uftrace]: https://github.com/CppCon/CppCon2016/blob/master/Lightning%20Talks%20and%20Lunch%20Sessions/uftrace%20-%20A%20function%20graph%20tracer%20C%20C++%20userspace%20programs/uftrace%20-%20A%20function%20graph%20tracer%20C%20C++%20userspace%20programs%20-%20Namhyung%20Kim%20and%20Honggyu%20Kim%20-%20CppCon%202016.pdf
[uftrace_video]: https://www.youtube.com/watch?v=LNav5qvyK7I
[uftrace_repo]: https://github.com/bisco/uftrace

[accumulate]: https://github.com/CppCon/CppCon2016/blob/master/Presentations/accumulate%20-%20Exploring%20an%20Algorithmic%20Empire/accumulate%20-%20Exploring%20an%20Algorithmic%20Empire%20-%20Ben%20Deane%20-%20CppCon%202016.pdf
[accumulate_video]: https://www.youtube.com/watch?v=B6twozNPUoA

[game_engine]: https://github.com/CppCon/CppCon2016/blob/master/Presentations/Game%20Engine%20Using%20C++11/Game%20Engine%20Using%20C++11%20-%20Jason%20Jurecka%20-%20CppCon%202016.pdf
[game_engine_video]: https://www.youtube.com/watch?v=8AjRD6mU96s

[oom]: https://github.com/CppCon/CppCon2016/blob/master/Presentations/Out%20of%20memory%20-%20Business%20as%20usual/Out%20of%20memory%20-%20Business%20as%20usual%20-%20Sergey%20Zubkov%20-%20CppCon%202016.pdf

[r6]: https://github.com/CppCon/CppCon2016/blob/master/Presentations/Rainbow%20Six%20Siege%20-%20Quest%20for%20Performance/Rainbow%20Six%20Siege%20-%20Quest%20for%20Performance%20-%20Nicolas%20Fleury%20-%20CppCon%202016.pdf
[r6_video]: https://www.youtube.com/watch?v=tD4xRNB0M_Q&index=95&list=PLHTh1InhhwT7J5jl4vAhO1WvGHUUFgUQH

[concurrency]: https://github.com/CppCon/CppCon2016/blob/master/Presentations/The%20Continuing%20Future%20of%20Concurrency%20in%20C++/The%20Continuing%20Future%20of%20Concurrency%20in%20C++%20-%20Anthony%20Williams%20-%20CppCon%202016.pdf
[concurrency_video]: https://www.youtube.com/watch?v=FaHJOkOrfNo&index=50&list=PLHTh1InhhwT7J5jl4vAhO1WvGHUUFgUQH

[exception]: https://github.com/CppCon/CppCon2016/blob/master/Presentations/The%20Exception%20Situation/The%20Exception%20Situation%20-%20Patrice%20Roy%20-%20CppCon%202016.pdf
[exception_video]: https://www.youtube.com/watch?v=Fno6suiXLPs&index=42&list=PLHTh1InhhwT7J5jl4vAhO1WvGHUUFgUQH

[heterogeneous]: https://github.com/CppCon/CppCon2016/blob/master/Presentations/Towards%20Heterogeneous%20Programming%20in%20C++/Towards%20Heterogeneous%20Programming%20in%20C++%20-%20Gordon%20Brown%20and%20Michael%20Wong%20-%20CppCon%202016.pdf
[heterogeneous_video]: https://www.youtube.com/watch?v=0Thv72yhxxw&index=25&list=PLHTh1InhhwT7J5jl4vAhO1WvGHUUFgUQH

