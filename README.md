# Free-Huges-Pet-Simulator-99
HUGES FAST
]]--

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


