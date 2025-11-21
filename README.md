# gothic-csharp-dojo ⛩️

`gothic-csharp-dojo` is my public C# / .NET dojo.

I’m building it for myself, but I’m sharing it so others can also:

- Use the topics as a learning path or quick refresher  
- Copy small examples and experiment with them  

Over time, this README should become a compact “C# dojo handbook” that anyone can read from top to bottom or jump into a single topic.

---

## How this repo is organized

I group everything into three parts:

- **Fundamentals** – language basics and core concepts  
- **Core** – everyday skills used in real projects  
- **Advanced** – deeper runtime, performance, and architecture topics  

For each topic the goal is:

- A short explanation, in plain language  
- One or two focused C# examples  
- A few notes: when to use it, when to avoid it, and common traps  

---

## Topics

### 1. Fundamentals

**1.1 Types**  
- Value vs reference types  
- Nullable value types  
- Basic idea of stack/heap and “copy vs share”  
(TODO)

**1.2 Constructs**  
- Operators  
- `if`, `switch`, switch expressions  
- Loops (`while`, `do-while`, `for`, `foreach`)  
- `break`, `continue`, `return`

**1.3 Expressions**  
- `is`, `as`, member access  
- Basic pattern matching  
- Collection expressions

**1.4 OOP basics**  
- Classes, structs, records  
- Constructors, properties, methods  
- Interfaces, inheritance, polymorphism

**1.5 Collections (basics)**  
- Arrays  
- `List<T>`  
- `Dictionary<TKey,TValue>`  
- `HashSet<T>`  
- Queues and stacks

**1.6 Error handling**  
- `try` / `catch` / `finally`  
- Filters (`when`)  
- Throwing and rethrowing cleanly

---

### 2. Core

**2.1 General language features**  
- Tuples  
- Attributes  
- Regex (basic usage)  
- Generic constraints and variance  
- `ref` returns, `ref struct`, `record struct`, primary constructors  
- Extension methods/members 

**2.2 Collections (intermediate)**  
- Read-only collections  
- Concurrent collections  
- Immutable collections  
- Frozen collections

**2.3 Async programming (core)**  
- Threads, ThreadPool, `Task`  
- `async` / `await`, `ValueTask`  
- Async streams (`IAsyncEnumerable<T>`, `await foreach`)  
- `Parallel` class

**2.4 Thread synchronization (core)**  
- `volatile`, `Interlocked`  
- `lock` (and `Monitor`)  
- `SemaphoreSlim`

**2.5 Memory management (core)**  
- Finalizers  
- `IDisposable`, dispose pattern  
- GC basics (generations, when it runs)

**2.6 LINQ (aggregate functions)**  
- `Count`, `Min`, `Max`, `Sum`, `Average`  
- `Aggregate`  
- Deferred vs immediate execution

---

### 3. Advanced

**3.1 General advanced features**  
- Iterators (`yield`)  
- `IAsyncDisposable`  
- Default interface members  
- Interpolated string handlers  
- `CallerArgumentExpression`

**3.2 Advanced async**  
- Channels  
- `CancellationTokenSource`, linked tokens  
- `TaskCompletionSource`  
- PLINQ

**3.3 Advanced thread synchronization**  
- `ManualResetEvent`, `AutoResetEvent`  
- `Semaphore` vs `SemaphoreSlim`  
- `Mutex`, `Monitor` internals

**3.4 Advanced memory and performance**  
- `Span<T>`, `Memory<T>`  
- `stackalloc`, inline arrays, unsafe code (carefully)  
- GC generations, LOH, allocation strategies

---

## How to use this README

- You can treat it as a small C# handbook and topic map.  
- When there are examples under a topic, you can:
  - Copy the code into a `.cs` file  
  - Run it with the .NET SDK (for example, using `dotnet run` on that file, depending on your setup)  

I will fill the topics gradually.  
You are welcome to follow along, fork it, or adapt the structure for your own C# dojo.
