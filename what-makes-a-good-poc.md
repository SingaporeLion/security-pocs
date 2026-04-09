## What makes a good PoC
A good PoC should reduce doubt, reduce reviewer effort, and make the observed failure impossible to dismiss.

1. **Confirmed behavior first**  
   Start by showing what actually happens, not what you think might happen.

2. **Minimal reproduction path**  
   Keep the setup as small as possible so the issue is easy to run and verify.

3. **Explicit preconditions**  
   Make it clear what must already be true before the issue can occur.

4. **Observed vs expected result**  
   Show the exact gap between protocol behavior and intended behavior.

5. **Impact bridge**  
   Explain why the reproduced failure matters in practice, not just technically.

6. **No hidden assumptions**  
   A strong PoC should not depend on vague environment details or undocumented behavior.

7. **Judge-friendly structure**  
   The reviewer should be able to understand the issue quickly without reverse-engineering your writeup.

8. **Root cause stays separate from proof**  
   First prove the issue exists, then explain why it likely happens.
