# Bitcoins-Mining-Simulator

Code is not allowed to upload to Github yet.
Following are my learning tips:


1.Cryptographic hash function in Elixir/Erlang
  Most Erland modules can be accessed by Elixir, usage:   :crypto
  hash algorithms:
  :md5
  :ripedmd160
  :sha(SHA-1)
  :sha224(SHA-2)
  :sha256(SHA-2)
  :sha384(SHA-2)
  :sha512(SHA-2)
  
  Usage Example:
  - No-streaming hashing: 
 iex(3)> :crypto.hash(:sha256, "Diane2017") |> Base.encode16 |> String.downcase

2. Random function in Elixir
  Random module is also based on Erlang's modules. 
  x = Random.rand            # random number between 0.0 ~ 1.0
  x = Ramdom.rand(:normal)   # Random number in normally-distributed range, -1..1 is one sigma
  n = Random.rand(5)         #
  n = Random.rand(5, 10) 

  
  
