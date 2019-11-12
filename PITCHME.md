## Test Driven Development Go
### Chris Bellamy
---
#### Software development process 
#### Emphasis on short development cycles
#### Requirements focused
#### Attributed to American software engineer Kent Beck
---
# Tenants of TDD
---
1. You are not allowed to write any production code unless it is to make a failing unit test pass.
2. You are not allowed to write any more of a unit test than is sufficient to fail; and compilation failures are failures.
3. You are not allowed to write any more production code than is sufficient to pass the one failing unit test.
---
# What usually happens
---
1. Write tests
2. Run tests **ensure it fails!**
3. Write some code 
4. Run tests **ensure it passes!**
5. Refactor code
6. GOTO 1
---
### So far so good, but what does this have to do with Go?
---
### Powerful testing package
### Like functions, testing is also a first class citizen in Go
### Can start writing tests before you even think about touching main
---
# It's ideal for TDD
---
Functional code makes testing easy.
As long as your functions match the interface signature it's easy to mock
The standard library makes this easy.
Dependency Injection is EASY - No frameworks!
---
io.Writer

Note: 
- https://quii.gitbook.io/learn-go-with-tests/go-fundamentals/dependency-injection
---
### Test Contravariance
Separate tests from implementation
Call private members directly
No need for complex abstractions just to make code testable
Note:
- https://blog.cleancoder.com/uncle-bob/2017/10/03/TestContravariance.html
---
# But why TDD?

"It's too slow"
"It costs too much"
"It's a waste of time"
"spend more time testing than actually writing code"
---