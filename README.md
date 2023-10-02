# Writing Good Documentaion

## Step 1 - Using Codelocks.

- Codelocks in markdown make it *very* easy for tech people to **copy, paste, share** code.(`)
- A good __Cloud Engineers__ uses Codeblocks whenever possible.
- Because it allows others to copy and paste their code to replicate or rrasearch issues. (')

```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

result = factorial(number)
puts "The factorial of #{number} is #{result}.
```
![download](https://github.com/Oksana-Orysyk/github-docs-example/assets/137808414/cb617b9a-7df5-4687-ab59-f0135ab10269)
To see picture ![]() 
<img src="https://example.com/image.png" alt="Image" width="300" height="200" />

_download](https://github.com/Oksana-Orysyk/github-docs-example/assets/137808414/cb617b9a-7df5-4687-ab59-f0135ab10269

With single quotations (which incorrect) '''
With backticks ``

def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

result = factorial(number)
puts "The factorial of #{number} is #{result}."

>Good Clod Engineers use codeblocks for both Code and Errors that appears in the console.
- Here is an example of use a codeblock for an error that appears in bash 
```bash

NameError: undefined local variable or method `some_undefined_variable' for main:Object
```

When you can you should attemp to apply syntax highlightsing to your coideblocks (ruby/ python)

## References 
- [GitHub Oksana(GitHub flavores markdown)](https://github.com/Oksana-Orysyk/github-docs-example/edit/main/README.md#writing-good-documentaion)
- [GitHub drgdrfhbg] https://github.github.com/gfm/

