# EJS PARTIALS
Partials come in handy when you want to reuse the same HTML across multiple views. **Think of partials as functions**, they make large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in. Instead, you define that reusable bundle of code in a file andinclude it wherever you need it.

![#](https://res.cloudinary.com/practicaldev/image/fetch/s--NcyF1ajR--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/gk1bxrwovuxzc5gnu6g7.png)

Note: The` <%- %>` tags allow us to output the unescaped content onto the page (notice the -). This is important when using the `include()` statement since you don’t want EJS to escape your HTML characters like `<, >`, etc…