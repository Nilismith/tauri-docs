---
title: "struct.AppBuilder"
---

Struct [tauri](/api/rust/tauri/index.html)::[AppBuilder](/api/rust/tauri/)
==========================================================================

```rust
pub struct AppBuilder { /\* fields omitted \*/ }
```

Methods
-------

### <code>impl [AppBuilder](/api/rust/tauri/../tauri/struct.AppBuilder.html "struct tauri::AppBuilder")</code>

#### <code>pub fn [new](/api/rust/tauri/about:blank#method.new)() -&gt; Self</code>

#### <code>pub fn [invoke_handler](/api/rust/tauri/about:blank#method.invoke_handler)&lt;F: [FnMut](https://doc.rust-lang.org/nightly/core/ops/function/trait.FnMut.html "trait core::ops::function::FnMut")(&mut WebView&lt;[()](https://doc.rust-lang.org/nightly/std/primitive.unit.html)&gt;, &[str](https://doc.rust-lang.org/nightly/std/primitive.str.html)) -&gt; [Result](https://doc.rust-lang.org/nightly/core/result/enum.Result.html "enum core::result::Result")&lt;[()](https://doc.rust-lang.org/nightly/std/primitive.unit.html), [String](https://doc.rust-lang.org/nightly/alloc/string/struct.String.html "struct alloc::string::String")&gt; + 'static&gt;(&lt;br/&gt;    self,&lt;br/&gt;    invoke_handler: F&lt;br/&gt;) -&gt; Self</code>

#### <code>pub fn [setup](/api/rust/tauri/about:blank#method.setup)&lt;F: [FnMut](https://doc.rust-lang.org/nightly/core/ops/function/trait.FnMut.html "trait core::ops::function::FnMut")(&mut WebView&lt;[()](https://doc.rust-lang.org/nightly/std/primitive.unit.html)&gt;, [String](https://doc.rust-lang.org/nightly/alloc/string/struct.String.html "struct alloc::string::String")) + 'static&gt;(&lt;br/&gt;    self,&lt;br/&gt;    setup: F&lt;br/&gt;) -&gt; Self</code>

#### <code>pub fn [splashscreen_html](/api/rust/tauri/about:blank#method.splashscreen_html)(self, html: &[str](https://doc.rust-lang.org/nightly/std/primitive.str.html)) -&gt; Self</code>

#### <code>pub fn [build](/api/rust/tauri/about:blank#method.build)(self) -&gt; [App](/api/rust/tauri/../tauri/struct.App.html "struct tauri::App")</code>

Trait Implementations
---------------------

### <code>impl [Default](https://doc.rust-lang.org/nightly/core/default/trait.Default.html "trait core::default::Default") for [AppBuilder](/api/rust/tauri/../tauri/struct.AppBuilder.html "struct tauri::AppBuilder")</code>

#### <code>fn [default](https://doc.rust-lang.org/nightly/core/default/trait.Default.html#tymethod.default)() -&gt; [AppBuilder](/api/rust/tauri/../tauri/struct.AppBuilder.html "struct tauri::AppBuilder")</code>

Returns the "default value" for a type. [Read more](https://doc.rust-lang.org/nightly/core/default/trait.Default.html#tymethod.default)

Auto Trait Implementations
--------------------------

### <code>impl 	&#33;[RefUnwindSafe](https://doc.rust-lang.org/nightly/std/panic/trait.RefUnwindSafe.html "trait std::panic::RefUnwindSafe") for [AppBuilder](/api/rust/tauri/../tauri/struct.AppBuilder.html "struct tauri::AppBuilder")</code>

### <code>impl 	&#33;[Send](https://doc.rust-lang.org/nightly/core/marker/trait.Send.html "trait core::marker::Send") for [AppBuilder](/api/rust/tauri/../tauri/struct.AppBuilder.html "struct tauri::AppBuilder")</code>

### <code>impl 	&#33;[Sync](https://doc.rust-lang.org/nightly/core/marker/trait.Sync.html "trait core::marker::Sync") for [AppBuilder](/api/rust/tauri/../tauri/struct.AppBuilder.html "struct tauri::AppBuilder")</code>

### <code>impl [Unpin](https://doc.rust-lang.org/nightly/core/marker/trait.Unpin.html "trait core::marker::Unpin") for [AppBuilder](/api/rust/tauri/../tauri/struct.AppBuilder.html "struct tauri::AppBuilder")</code>

### <code>impl 	&#33;[UnwindSafe](https://doc.rust-lang.org/nightly/std/panic/trait.UnwindSafe.html "trait std::panic::UnwindSafe") for [AppBuilder](/api/rust/tauri/../tauri/struct.AppBuilder.html "struct tauri::AppBuilder")</code>

Blanket Implementations
-----------------------

### <code>impl&lt;T&gt; [Any](https://doc.rust-lang.org/nightly/core/any/trait.Any.html "trait core::any::Any") for T where&lt;br/&gt;    T: 'static + ?[Sized](https://doc.rust-lang.org/nightly/core/marker/trait.Sized.html "trait core::marker::Sized"),</code> 

#### <code>fn [type_id](https://doc.rust-lang.org/nightly/core/any/trait.Any.html#tymethod.type_id)(&self) -&gt; [TypeId](https://doc.rust-lang.org/nightly/core/any/struct.TypeId.html "struct core::any::TypeId")</code>

Gets the <code>TypeId</code> of <code>self</code>. [Read more](https://doc.rust-lang.org/nightly/core/any/trait.Any.html#tymethod.type_id)

### <code>impl&lt;T&gt; [Borrow](https://doc.rust-lang.org/nightly/core/borrow/trait.Borrow.html "trait core::borrow::Borrow")&lt;T&gt; for T where&lt;br/&gt;    T: ?[Sized](https://doc.rust-lang.org/nightly/core/marker/trait.Sized.html "trait core::marker::Sized"),</code> 

#### <code>fn [borrow](https://doc.rust-lang.org/nightly/core/borrow/trait.Borrow.html#tymethod.borrow)(&self) -&gt; [&](https://doc.rust-lang.org/nightly/std/primitive.reference.html)T</code>

Immutably borrows from an owned value. [Read more](https://doc.rust-lang.org/nightly/core/borrow/trait.Borrow.html#tymethod.borrow)

### <code>impl&lt;T&gt; [BorrowMut](https://doc.rust-lang.org/nightly/core/borrow/trait.BorrowMut.html "trait core::borrow::BorrowMut")&lt;T&gt; for T where&lt;br/&gt;    T: ?[Sized](https://doc.rust-lang.org/nightly/core/marker/trait.Sized.html "trait core::marker::Sized"),</code> 

#### <code>fn [borrow_mut](https://doc.rust-lang.org/nightly/core/borrow/trait.BorrowMut.html#tymethod.borrow_mut)(&mut self) -&gt; [&mut](https://doc.rust-lang.org/nightly/std/primitive.reference.html) T</code>

Mutably borrows from an owned value. [Read more](https://doc.rust-lang.org/nightly/core/borrow/trait.BorrowMut.html#tymethod.borrow_mut)

### <code>impl&lt;T&gt; [From](https://doc.rust-lang.org/nightly/core/convert/trait.From.html "trait core::convert::From")&lt;T&gt; for T</code>

#### <code>fn [from](https://doc.rust-lang.org/nightly/core/convert/trait.From.html#tymethod.from)(t: T) -&gt; T</code>

Performs the conversion.

### <code>impl&lt;T, U&gt; [Into](https://doc.rust-lang.org/nightly/core/convert/trait.Into.html "trait core::convert::Into")&lt;U&gt; for T where&lt;br/&gt;    U: [From](https://doc.rust-lang.org/nightly/core/convert/trait.From.html "trait core::convert::From")&lt;T&gt;,</code> 

#### <code>fn [into](https://doc.rust-lang.org/nightly/core/convert/trait.Into.html#tymethod.into)(self) -&gt; U</code>

Performs the conversion.

### <code>impl&lt;T, U&gt; [TryFrom](https://doc.rust-lang.org/nightly/core/convert/trait.TryFrom.html "trait core::convert::TryFrom")&lt;U&gt; for T where&lt;br/&gt;    U: [Into](https://doc.rust-lang.org/nightly/core/convert/trait.Into.html "trait core::convert::Into")&lt;T&gt;,</code> 

#### <code>type [Error](https://doc.rust-lang.org/nightly/core/convert/trait.TryFrom.html#associatedtype.Error) = [Infallible](https://doc.rust-lang.org/nightly/core/convert/enum.Infallible.html "enum core::convert::Infallible")</code>

The type returned in the event of a conversion error.

#### <code>fn [try_from](https://doc.rust-lang.org/nightly/core/convert/trait.TryFrom.html#tymethod.try_from)(value: U) -&gt; [Result](https://doc.rust-lang.org/nightly/core/result/enum.Result.html "enum core::result::Result")&lt;T, &lt;T as [TryFrom](https://doc.rust-lang.org/nightly/core/convert/trait.TryFrom.html "trait core::convert::TryFrom")&lt;U&gt;&gt;::[Error](https://doc.rust-lang.org/nightly/core/convert/trait.TryFrom.html#associatedtype.Error "type core::convert::TryFrom::Error")&gt;</code>

Performs the conversion.

### <code>impl&lt;T, U&gt; [TryInto](https://doc.rust-lang.org/nightly/core/convert/trait.TryInto.html "trait core::convert::TryInto")&lt;U&gt; for T where&lt;br/&gt;    U: [TryFrom](https://doc.rust-lang.org/nightly/core/convert/trait.TryFrom.html "trait core::convert::TryFrom")&lt;T&gt;,</code> 

#### <code>type [Error](https://doc.rust-lang.org/nightly/core/convert/trait.TryInto.html#associatedtype.Error) = &lt;U as [TryFrom](https://doc.rust-lang.org/nightly/core/convert/trait.TryFrom.html "trait core::convert::TryFrom")&lt;T&gt;&gt;::[Error](https://doc.rust-lang.org/nightly/core/convert/trait.TryFrom.html#associatedtype.Error "type core::convert::TryFrom::Error")</code>

The type returned in the event of a conversion error.

#### <code>fn [try_into](https://doc.rust-lang.org/nightly/core/convert/trait.TryInto.html#tymethod.try_into)(self) -&gt; [Result](https://doc.rust-lang.org/nightly/core/result/enum.Result.html "enum core::result::Result")&lt;U, &lt;U as [TryFrom](https://doc.rust-lang.org/nightly/core/convert/trait.TryFrom.html "trait core::convert::TryFrom")&lt;T&gt;&gt;::[Error](https://doc.rust-lang.org/nightly/core/convert/trait.TryFrom.html#associatedtype.Error "type core::convert::TryFrom::Error")&gt;</code>

Performs the conversion.

### <code>impl&lt;V, T&gt; VZip&lt;V&gt; for T where&lt;br/&gt;    V: MultiLane&lt;T&gt;,</code> 

#### <code>fn [vzip](/api/rust/tauri/about:blank#method.vzip)(self) -&gt; V</code>
      