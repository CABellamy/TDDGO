# Test Driven Development Go
### Chris Bellamy
---
#### Software development process 

#### Emphasis on short development cycles

#### Requirements focused

#### Attributed to American software engineer Kent Beck
---
# Tenants of TDD
---
``` 1. You are not allowed to write any production code unless it is to make a failing unit test pass.
  2. You are not allowed to write any more of a unit test than is sufficient to fail; and compilation failures are failures.
  3. You are not allowed to write any more production code than is sufficient to pass the one failing unit test.```
---
1. Write tests
2. Run tests **ensure it fails!**
3. Write some code 
4. Run tests **ensure it passes!**
5. Refactor code
6. Repeat
---
# So far so good, but what does this have to do with Go?
---
### Like functions, testing is also a first class citizen in Go
### Powerful testing package
### Can start writing tests before you even think about touching main
---
# It's ideal for TDD
---
# But why TDD?