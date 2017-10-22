
### Checklist

Please make sure following is installed:
- VisualStudioCode
- Node JS v. 8.x
- Git

Thx.

Note:
- use any IDE you like. I can help with VSC and Webstorm
- any questions why we need Node JS?

---

### Hello

 - Kirill Gerasimenko | Kyrylo Herasymenko
 - Web-developer since 2003
 - Now team lead at Global Logic
 - 4 projects with Angular JS, 1.5 projects with Angular

---

 ### Course requirements

 - Knowledge of JavaScript
 - Knowledge of ES6 is a plus, but not mandatory
 - Good English reading skills

---

<span class="menu-title" style="display: none">Intro</span>

<h3 style="font-size:160px">Angular 4</h3>

<div class="fragment">
  <div style="color:gray">Let's learn it now,<div>
  <div style="color:gray">before it's <s>too late</s> <b>Angular 5</b></div>
</div>

Note:
- angular 1.X, then 2 and now it's 4
- Angular 5 will not bring too much breaking changes

---

<span class="menu-title" style="display: none">What's inside</span>

### What's inside?

<ul>
  <li class="fragment">Reactivity</li>
  <li class="fragment">Components</li>
  <li class="fragment">TypeScript ?!</li>
</ul>

Note:
- reactivity == SPA
- "responsive" system is quick to react
- components. they are everywhere.
- google "web components"
- TS can be seamless
- TS does not add more complexity to solve rare issues
- we need smth. to transpile ES6 anyway, right?

+++

### ES6 or TypeScript?

```JavaScript
import { Component } from '@angular/core';

export class AppComponent {
  title = 'the app';
}
```
<div class="fragment">Who knows...</div>

+++

### well, that's TS!

```JavaScript
import { Component } from '@angular/core';

@Component({
  selector: 'app-root',
  templateUrl: './app.component.html',
  styleUrls: ['./app.component.css']
})
export class AppComponent {
  title = 'the app';
}
```
<div class="fragment">or maybe ES7 decorators? ;)</div>

Note:
- consider TS is a one more way to write ES7 today
- plus types can be helpful. e.g. for code hints
- if you will have questions about TS - ask, or google
- but most likely you will not
---
<span class="menu-title" style="display: none">@angular/cli</span>

### LET'S START

`npm install -g @angular/cli`

Note:
- code generation
- dev. web server
- code linting
- will see it later
- about re-inventing the wheel and re-using pre-configured popular tools under the hood

---
<span class="menu-title" style="display: none">The questions</span>

### TIME TO MAKE DECISIONS

- how to structure my project?
- which build system should I use?
- what about dev. server?
- hot reload?
- maybe there is some starter kit?
- ... or maybe Yeoman generator?
- which one to choose?

---
<span class="menu-title" style="display: none">The answer</span>

### NG NEW

```
$> ng new my-project
```

That's it.

Now let's dive into the code!

---

### What We Just Learnt

<ul>
  <li class="fragment">Always start with smth. which works</li>
  <li class="fragment">Set your expectations before coding</li>
  <li class="fragment">Write as less code as possible</li>
  <li class="fragment">Compare result with your expectations</li>
  <li class="fragment">Component is a thing-in-itself</li>
  <li class="fragment">Content. State. Behavior. Style.</li>
  <li class="fragment">Components are able to communicate</li>
  <li class="fragment">Start small, start simple</li>
  <li class="fragment">Everything big is built from small pieces</li>
</ul>


---

### Course Overview

<ul>
  <li class="fragment">Components</li>
  <li class="fragment">Routing</li>
  <li class="fragment">Modules</li>
  <li class="fragment">Services and DI</li>
  <li class="fragment">HTTP and Auth</li>
  <li class="fragment">Building for production</li>
</ul>
<div class="fragment">directives, pipes, observables, unit-testing etc., etc.</div>

---

### Schedule

- MON 19:00 - 20:30
- WED 19:00 - 20:30
- SAT 14:00 - 15:30
