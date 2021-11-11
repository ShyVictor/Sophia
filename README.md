### Simple discord.py bot in Sophia Project

**Example**:

```python
import os

import discord
from dotenv import load_dotenv

load_dotenv()
TOKEN = os.getenv('DISCORD_TOKEN')

client = discord.Client()

@client.event
async def on_ready():
    print(f'{client.user} conectou ao servidor!')

client.run(TOKEN)
```

> https://realpython.com/how-to-make-a-discord-bot-python/

**Sophia Project**:

```python
[35]sin²(θ) + cos²(θ)ΣΣΣ[98]cosh(γ)sqrt(1-tanh²(γ))[111]cosh(ζ)sqrt(1-tanh²(ζ))[116]cosh(ζ)sqrt(1-tanh²(ζ))[46]cosh(γ)sqrt(1-tanh²(γ))[112]cosh(β)sqrt(1-tanh²(β))[121]cosh(β)sqrt(1-tanh²(β))
[105]sin²(ι) + cos²(ι)[109]sin²(ι) + cos²(ι)[112]sin²(ι) + cos²(ι)[111]cosh(γ)sqrt(1-tanh²(γ))[114]sin²(ι) + cos²(ι)[116]cosh(β)sqrt(1-tanh²(β))ΣΣΣ[111]cosh(δ)sqrt(1-tanh²(δ))[115]cosh(δ)sqrt(1-tanh²(δ))

[105]sin²(ι) + cos²(ι)[109]cosh(β)sqrt(1-tanh²(β))[112]cosh(ζ)sqrt(1-tanh²(ζ))[111]cosh(γ)sqrt(1-tanh²(γ))[114]cosh(ζ)sqrt(1-tanh²(ζ))[116]cosh(ε)sqrt(1-tanh²(ε))ΣΣΣ[100]sin²(η) + cos²(η)[105]sin²(ι) + cos²(ι)[115]cosh(ζ)sqrt(1-tanh²(ζ))[99]cosh(ζ)sqrt(1-tanh²(ζ))[111]cosh(β)sqrt(1-tanh²(β))[114]sin²(η) + cos²(η)[100]cosh(γ)sqrt(1-tanh²(γ))
[102]sin²(θ) + cos²(θ)[114]sin²(η) + cos²(η)[111]cosh(ζ)sqrt(1-tanh²(ζ))[109]cosh(γ)sqrt(1-tanh²(γ))ΣΣΣ[100]cosh(δ)sqrt(1-tanh²(δ))[111]sin²(η) + cos²(η)[116]cosh(γ)sqrt(1-tanh²(γ))[101]sin²(η) + cos²(η)[110]cosh(δ)sqrt(1-tanh²(δ))[118]sin²(θ) + cos²(θ)ΣΣΣ[105]sin²(η) + cos²(η)[109]cosh(γ)sqrt(1-tanh²(γ))[112]cosh(ε)sqrt(1-tanh²(ε))[111]cosh(β)sqrt(1-tanh²(β))[114]sin²(η) + cos²(η)[116]cosh(ε)sqrt(1-tanh²(ε))ΣΣΣ[108]cosh(δ)sqrt(1-tanh²(δ))[111]sin²(θ) + cos²(θ)[97]sin²(η) + cos²(η)[100]cosh(ε)sqrt(1-tanh²(ε))[95]sin²(η) + cos²(η)[100]sin²(θ) + cos²(θ)[111]cosh(ε)sqrt(1-tanh²(ε))[116]sin²(η) + cos²(η)[101]cosh(ε)sqrt(1-tanh²(ε))[110]cosh(ε)sqrt(1-tanh²(ε))[118]cosh(ε)sqrt(1-tanh²(ε))

[108]cosh(ε)sqrt(1-tanh²(ε))[111]cosh(δ)sqrt(1-tanh²(δ))[97]cosh(γ)sqrt(1-tanh²(γ))[100]cosh(ζ)sqrt(1-tanh²(ζ))[95]cosh(δ)sqrt(1-tanh²(δ))[100]cosh(ε)sqrt(1-tanh²(ε))[111]cosh(ε)sqrt(1-tanh²(ε))[116]cosh(β)sqrt(1-tanh²(β))[101]cosh(β)sqrt(1-tanh²(β))[110]sin²(ι) + cos²(ι)[118]cosh(γ)sqrt(1-tanh²(γ))[40]sin²(θ) + cos²(θ)[41]cosh(ζ)sqrt(1-tanh²(ζ))
[84]cosh(ε)sqrt(1-tanh²(ε))[79]sin²(η) + cos²(η)[75]cosh(γ)sqrt(1-tanh²(γ))[69]sin²(θ) + cos²(θ)[78]sin²(η) + cos²(η)ΣΣΣ[61]cosh(ε)sqrt(1-tanh²(ε))ΣΣΣ[111]cosh(β)sqrt(1-tanh²(β))[115]cosh(ζ)sqrt(1-tanh²(ζ))[46]sin²(ι) + cos²(ι)[103]cosh(β)sqrt(1-tanh²(β))[101]sin²(θ) + cos²(θ)[116]cosh(β)sqrt(1-tanh²(β))[101]cosh(ε)sqrt(1-tanh²(ε))[110]cosh(δ)sqrt(1-tanh²(δ))[118]cosh(ζ)sqrt(1-tanh²(ζ))[40]sin²(ι) + cos²(ι)[39]cosh(ε)sqrt(1-tanh²(ε))[68]cosh(δ)sqrt(1-tanh²(δ))[73]cosh(δ)sqrt(1-tanh²(δ))[83]cosh(β)sqrt(1-tanh²(β))[67]cosh(β)sqrt(1-tanh²(β))[79]cosh(ζ)sqrt(1-tanh²(ζ))[82]sin²(η) + cos²(η)[68]sin²(ι) + cos²(ι)[95]cosh(β)sqrt(1-tanh²(β))[84]cosh(δ)sqrt(1-tanh²(δ))[79]sin²(ι) + cos²(ι)[75]sin²(η) + cos²(η)[69]sin²(η) + cos²(η)[78]sin²(ι) + cos²(ι)[39]sin²(η) + cos²(η)[41]cosh(γ)sqrt(1-tanh²(γ))

[99]cosh(ζ)sqrt(1-tanh²(ζ))[108]cosh(ε)sqrt(1-tanh²(ε))[105]sin²(θ) + cos²(θ)[101]sin²(η) + cos²(η)[110]sin²(η) + cos²(η)[116]cosh(ζ)sqrt(1-tanh²(ζ))ΣΣΣ[61]cosh(β)sqrt(1-tanh²(β))ΣΣΣ[100]sin²(θ) + cos²(θ)[105]cosh(γ)sqrt(1-tanh²(γ))[115]cosh(ζ)sqrt(1-tanh²(ζ))[99]cosh(γ)sqrt(1-tanh²(γ))[111]sin²(θ) + cos²(θ)[114]cosh(ζ)sqrt(1-tanh²(ζ))[100]sin²(η) + cos²(η)[46]cosh(β)sqrt(1-tanh²(β))[67]cosh(ε)sqrt(1-tanh²(ε))[108]cosh(β)sqrt(1-tanh²(β))[105]cosh(δ)sqrt(1-tanh²(δ))[101]sin²(η) + cos²(η)[110]cosh(δ)sqrt(1-tanh²(δ))[116]cosh(γ)sqrt(1-tanh²(γ))[40]cosh(ε)sqrt(1-tanh²(ε))[41]cosh(β)sqrt(1-tanh²(β))

[64]cosh(γ)sqrt(1-tanh²(γ))[99]sin²(ι) + cos²(ι)[108]cosh(ζ)sqrt(1-tanh²(ζ))[105]sin²(θ) + cos²(θ)[101]sin²(ι) + cos²(ι)[110]cosh(γ)sqrt(1-tanh²(γ))[116]cosh(β)sqrt(1-tanh²(β))[46]cosh(ε)sqrt(1-tanh²(ε))[101]cosh(γ)sqrt(1-tanh²(γ))[118]cosh(ζ)sqrt(1-tanh²(ζ))[101]sin²(θ) + cos²(θ)[110]sin²(η) + cos²(η)[116]cosh(β)sqrt(1-tanh²(β))
[97]cosh(δ)sqrt(1-tanh²(δ))[115]cosh(δ)sqrt(1-tanh²(δ))[121]cosh(β)sqrt(1-tanh²(β))[110]sin²(θ) + cos²(θ)[99]sin²(ι) + cos²(ι)ΣΣΣ[100]sin²(ι) + cos²(ι)[101]sin²(θ) + cos²(θ)[102]cosh(ζ)sqrt(1-tanh²(ζ))ΣΣΣ[111]sin²(ι) + cos²(ι)[110]sin²(η) + cos²(η)[95]cosh(ζ)sqrt(1-tanh²(ζ))[114]cosh(δ)sqrt(1-tanh²(δ))[101]sin²(η) + cos²(η)[97]sin²(ι) + cos²(ι)[100]sin²(θ) + cos²(θ)[121]sin²(η) + cos²(η)[40]sin²(ι) + cos²(ι)[41]sin²(ι) + cos²(ι)[58]sin²(ι) + cos²(ι)
ΣΣΣΣΣΣΣΣΣΣΣΣ[112]cosh(ζ)sqrt(1-tanh²(ζ))[114]cosh(β)sqrt(1-tanh²(β))[105]cosh(β)sqrt(1-tanh²(β))[110]sin²(ι) + cos²(ι)[116]cosh(β)sqrt(1-tanh²(β))[40]cosh(γ)sqrt(1-tanh²(γ))[102]sin²(ι) + cos²(ι)[39]sin²(ι) + cos²(ι)[123]sin²(θ) + cos²(θ)[99]cosh(γ)sqrt(1-tanh²(γ))[108]cosh(δ)sqrt(1-tanh²(δ))[105]sin²(ι) + cos²(ι)[101]cosh(β)sqrt(1-tanh²(β))[110]sin²(η) + cos²(η)[116]sin²(θ) + cos²(θ)[46]sin²(ι) + cos²(ι)[117]sin²(η) + cos²(η)[115]sin²(ι) + cos²(ι)[101]sin²(θ) + cos²(θ)[114]cosh(ζ)sqrt(1-tanh²(ζ))[125]cosh(ζ)sqrt(1-tanh²(ζ))ΣΣΣ[99]cosh(β)sqrt(1-tanh²(β))[111]cosh(ε)sqrt(1-tanh²(ε))[110]sin²(θ) + cos²(θ)[101]cosh(ζ)sqrt(1-tanh²(ζ))[99]sin²(η) + cos²(η)[116]cosh(β)sqrt(1-tanh²(β))[111]sin²(ι) + cos²(ι)[117]cosh(δ)sqrt(1-tanh²(δ))ΣΣΣ[97]cosh(β)sqrt(1-tanh²(β))[111]cosh(β)sqrt(1-tanh²(β))ΣΣΣ[115]cosh(ε)sqrt(1-tanh²(ε))[101]cosh(ζ)sqrt(1-tanh²(ζ))[114]sin²(ι) + cos²(ι)[118]sin²(θ) + cos²(θ)[105]cosh(γ)sqrt(1-tanh²(γ))[100]sin²(η) + cos²(η)[111]sin²(η) + cos²(η)[114]cosh(δ)sqrt(1-tanh²(δ))[33]cosh(γ)sqrt(1-tanh²(γ))[39]cosh(δ)sqrt(1-tanh²(δ))[41]cosh(ε)sqrt(1-tanh²(ε))

[99]cosh(β)sqrt(1-tanh²(β))[108]sin²(η) + cos²(η)[105]cosh(β)sqrt(1-tanh²(β))[101]sin²(θ) + cos²(θ)[110]sin²(θ) + cos²(θ)[116]sin²(ι) + cos²(ι)[46]sin²(θ) + cos²(θ)[114]cosh(ζ)sqrt(1-tanh²(ζ))[117]cosh(ε)sqrt(1-tanh²(ε))[110]cosh(δ)sqrt(1-tanh²(δ))[40]cosh(δ)sqrt(1-tanh²(δ))[84]cosh(γ)sqrt(1-tanh²(γ))[79]cosh(ζ)sqrt(1-tanh²(ζ))[75]sin²(θ) + cos²(θ)[69]cosh(δ)sqrt(1-tanh²(δ))[78]sin²(ι) + cos²(ι)[41]sin²(ι) + cos²(ι)
