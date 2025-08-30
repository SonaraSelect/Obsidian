- Learn .net interview questions https://zerotomastery.io/blog/dot-NET-interview-questions/
- Learn C# pointers
- Write down all SimCorp SWE interview questions
- **Write down all special things the Circuit Sim uses**

- Learn boxing and unboxing
# C\#

- `dotnet new console` and `dotnet run` and `dotnet build`

`using` is like import and `namespace` is like package

Print with `Console.WriteLine()`

Typecasting `int valueD = (int)valueC`

**Override** works as `public override void ToString()`

Class extension `public class Dog : Animal`

yes its `bool`


PascalCase for public things, camelCase for private

Private fields are written like `_privateField`


## XML
- - `<summary>`: One-sentence what/why of the member.
- `<remarks>`: Longer notes, details, caveats.
- `<param name="x">…</param>`: Describe each parameter.
- `<returns>`: Describe the return value (omit for `void`).
- `<exception cref="T">…</exception>`: When/why a method throws.
- `<typeparam name="T">…</typeparam>` and `<typeparamref name="T"/>`: For generics.
- `<see cref="TypeOrMember"/>` / `<seealso cref="…"/>`: Cross-references.
- `<value>`: Docs for a property’s value.
- `<para>…</para>`: Paragraph breaks inside other tags.
- `<c>code</c>`: Inline code; `<code>…</code>` for blocks.
- `<inheritdoc/>`: Inherit docs from a base member/interface.
- `<include file="…" path="…"/>`: Pull text from an external XML file.
# My project uses


 

- Nullables
- Generic Types
- XML documentation
- internal access modifier
	- `FanOut { get; protected set; }`
- uses Dictionary
	- `public bool TryGetValue(TKey key, out TValue value);` WEIRD AF!!
	- `new Dictionary<string, Entity>(capacity: 100);`
	- inline declarations 
	- `newMap = new Dictionary<string, Entity>(capacity: 100);`
	- `sched[newLevel] = newMap;`
- virtual keyword
	- Allows for a method to be overridden
- Primary constructor 
	- `public class Gate(String name, GateType type) : Entity(name, type)`
- Method return shortcut
	- `internal override string PrintClass() => "Wire";`
- Python string f
	- `var bufName = $"BUF{inEntity.Name}{outEntity.Name}";`
- 

- [x] DataWrapper
- [x] Gate (ez)
- [x] GateType
- [ ] Wire (ez)
- [x] Entity (alm done)
- [ ] Circuit (largest)

- [ ] Maybe FanIn.Add should be protected?





- Add JUnit testing experience to resume