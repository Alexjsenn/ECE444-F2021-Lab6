# ECE444-F2021-Lab6: Alexander Senn
This has been copied and adapted from https://github.com/mjhea0/flaskr-tdd


Pros and cons of TDD:

TDD offers a lot of advantages when it comes to creating deterministic functions that don't have side effects, 
such as backend API calls or other related buisness logic. It forces the coder to define very strictly the behaviour
of the function before it is written, refactored, etc. This ensures that significant "planning" has gone into what the 
functionality required is, and is laid out and explicitly written down, This allows anyone else to look at a unit test 
and understand exactly what their code would have to do to ensure success. This also greatly improves efficiency in
collaborative environments.

However, there are some drawbacks. With respect to the same kind of deterministic functions that work well with TDD, 
there are sometimes certain behaviours that are not all foreseen, and if the attitude toward coding functional units
is solely centered around passing the test, corners may be cut. This might also make the quality of the code worse if 
significant refactoring is not performed. In addition, there are many components of front end systems that are significantly
more difficult to test. This is because a large part of frontend and UI design centeres around human experience, which is 
notoriously hard to quantify and encode into tests.
