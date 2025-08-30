# RSpec: Welcome to the RSpec Curriculum! 🎉

Ready to become a bug-busting, confidence-building, test-writing wizard? You’re in the right place! This curriculum is your step-by-step, laugh-along guide to learning automated testing with RSpec—the most popular, expressive, and downright delightful testing framework for Ruby and Rails.

---

## What is this Curriculum?

Think of this curriculum as your personal roadmap to testing greatness. Whether you’re brand new to automated testing or just want to level up your skills, you’ll find everything you need right here. We’ll go slow, we’ll go deep, and we’ll have fun along the way (because learning should never be boring).

## Why Learn RSpec?

Testing isn’t just about finding bugs (though that’s a nice perk). It’s about:

- Building confidence in your code (and yourself!)
- Making it easier to add new features without fear
- Collaborating with teammates who will thank you for your beautiful, well-tested code
- Sleeping better at night, knowing your app won’t explode at 2am

RSpec makes testing in Ruby and Rails clear, expressive, and—dare we say—fun. It’s like having a conversation with your code, and your code actually listens.

## How This Curriculum Works

- **Lessons**: Each lesson repo (ending in `-readme`) is a deep dive into a key concept. Lessons are written to be overly clear and verbose, with lots of examples, analogies, and practice prompts. You’ll learn not just the “how,” but the “why.”
- **Labs**: Each lab repo (ending in `-lab`) is a hands-on coding challenge. Labs are designed to help you practice what you’ve learned, step by step, with clear instructions and robust meta-specs to check your work. (No, the meta-specs won’t do your homework for you, but they’ll make sure you’re on the right track!)
- **No Solutions Provided**: You’ll be writing your own specs and, in some cases, your own code. This is intentional! The best way to learn testing is by doing it yourself. (Don’t worry, you’ll have plenty of guidance.)

## What You’ll Need

- **Ruby and Rails knowledge**: This curriculum assumes you already know how to write Ruby code and work with Rails. If you can make a class and run a migration, you’re good to go!
- **A willingness to experiment**: Don’t be afraid to try things, break things, and learn from mistakes. Testing is all about learning what your code does—and what it should do. (Bonus points for creative bug names.)

## How to Use This Curriculum

1. **Start with the lessons**: Read each lesson repo in order. Take your time with the examples and practice prompts. Don’t rush—testing is a marathon, not a sprint!
2. **Tackle the labs**: After each lesson or set of lessons, complete the corresponding lab. The labs are designed to reinforce and expand on what you’ve learned. Think of them as your testing gym—time to flex those RSpec muscles!
3. **Ask questions**: If you get stuck, review the lessons, experiment in IRB or your editor, and don’t hesitate to ask for help. (There are no silly questions, only untested code.)
4. **Reflect**: After each lesson and lab, take a moment to reflect on what you’ve learned. How does testing change the way you think about code? (Bonus: Write your reflections in a journal. Future You will be impressed.)

## The Journey Ahead

By the end of this curriculum, you’ll be able to:

- Write clear, effective RSpec tests for Ruby and Rails apps (and maybe even impress your friends)
- Understand and use a wide variety of RSpec matchers and features (so many matchers, so little time)
- Organize your test suite for maintainability and clarity (your future teammates will thank you)
- Approach new code with a testing mindset (like a code detective!)

Testing is a skill that will serve you for your entire career. It’s your secret weapon for building better software, faster. So grab your keyboard, your sense of humor, and let’s get started!

---

## Complete RSpec Curriculum

### Unit 1

- Lesson 1: Introduction to Testing and RSpec — What testing is, why we test, types of tests (unit, integration, system), and why RSpec is standard in Ruby/Rails.
- Lesson 2: Installing and Initializing RSpec — Installing RSpec gem, running `rspec --init`, exploring `spec/` folder structure, running the first test suite.
- Lab 1: Hello RSpec — Students write their first `describe`/`it`/`expect` specs against a simple Ruby class (e.g., Calculator).

### Unit 2

- Lesson 3: Test-Driven Development (TDD) — Red/Green/Refactor cycle, benefits of TDD, applying TDD to Ruby classes.
- Lesson 4: Examples and Expectations — `describe`, `context`, `it`, `expect`, `eq`, `eql`, `equal`.
- Lesson 5: Reading Failures & Debugging Specs — How to interpret RSpec’s error output to guide development.
- Lab 2: TDD a Small Ruby Class — Students TDD a Ruby class (e.g., Playlist, BankAccount, TodoList). Specs guide the implementation.

### Unit 3

- Lesson 6: Before/After Hooks and Instance Variables — Reducing duplication with `before`/`after` and instance variables.
- Lesson 7: let and let! — Lazy vs eager evaluation, why `let` is often better than instance variables.
- Lesson 8: Custom Error Messages & Helper Methods — Improving spec readability and clarity with helper methods and custom messages.
- Lab 3: Refactoring Specs for Readability — Students refactor messy specs into DRY, readable specs using hooks, `let`, and helpers.

### Unit 4

- Lesson 9: The context Method & Nested Describes — Organizing test cases with `context` and nested `describe`s.
- Lesson 10: Subjects (implicit & explicit) — `subject`, implicit vs explicit usage, one-liner syntax, `described_class`.
- Lesson 11: Shared Examples & Shared Context — Reusing test logic with `include_examples` and `include_context`.
- Lab 4: Organizing a Larger Spec Suite — Students write/refactor specs for a complex Ruby class (e.g., Deck of Cards, ShoppingCart). Must use contexts, subjects, shared examples.

### Unit 5

- Lesson 12: Equality & Comparison Matchers — `eq`, `eql`, `equal`, and comparison matchers.
- Lesson 13: Predicate Matchers & Truthiness — `be_truthy`, `be_falsey`, `be_nil`, `be_empty`, etc.
- Lesson 14: Collection & Attribute Matchers — `include`, `contain_exactly`, `have_attributes`, `start_with`, `end_with`.
- Lesson 15: Error & Change Matchers — `raise_error`, `change`, `respond_to`, `satisfy`, compound expectations.
- Lab 5: Matcher Playground — Students write specs using each matcher type against provided Ruby classes.

### Unit 6

- Lesson 16: Introduction to Test Doubles — What doubles are, why they’re useful, `double` method.
- Lesson 17: Allow, Receive, and Argument Matching — `allow(...).to receive`, return values, argument matchers.
- Lesson 18: Instance Doubles, Class Doubles, and Spies — Strict doubles, verifying interfaces, and spies for verifying interactions.
- Lab 6: Doubles & Mocks — Students test-drive a Ruby service object (e.g., Notifier or PaymentProcessor) using doubles and spies.

### Unit 7 (Rails)

- Lesson 19: RSpec in Rails — `rspec-rails` gem, folder structure, `rails generate rspec:install`.
- Lesson 20: Model Specs with Validations & Associations — Testing ActiveRecord models, validations, associations, and using FactoryBot.
- Lesson 21: Request Specs — Testing controllers and APIs with request specs.
- Lesson 22: System/Feature Specs — Testing user flows with Capybara.
- Lesson 23: Fixtures vs Factories — Comparing fixtures and factories, best practices with FactoryBot.
- Lab 7: Testing a Rails Mini-App — A Rails app (Blog with Users & Posts). Students write model, request, and feature specs.

### Unit 8

- Lesson 24: Writing Maintainable Test Suites — Best practices for organizing specs, avoiding over-mocking, focusing on behavior not implementation.
- Lab 8: Capstone – Add Specs to an Existing Project — Students return to a project they built earlier and add a full spec suite: unit, request, and system tests.

---

*Next: Dive into the first lesson, "Introduction to Testing and RSpec."*
