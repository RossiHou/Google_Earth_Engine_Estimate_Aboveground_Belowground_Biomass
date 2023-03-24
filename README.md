# aboveground_belowground_biomass

Because I see prof.Roman dataset only cover woody aboveground biomass.So I used gee to generate what I called the genius way to get the real-time(depending on the temporal resolution of remote sensing data) aboveground biomass and underground biomass. Instead of using ndvi and evil as the training dataset, I change it to the ecological factors, including "plant canopy surface water; latent heat net flux; root zone soil moisture"  as the better factors to predict the biomass.Here is the code. 
![图片](https://user-images.githubusercontent.com/76504267/227414309-cd85bdd5-a3de-4050-aded-9b5a7d0520f6.png)

