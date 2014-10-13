UIImage-ImageEffects
====================

Modified version of Apple's WWDC 2013 UIImage category, change

   NSUInteger radius = floor(inputRadius * 3. * sqrt(2 * M_PI) / 4 + 0.5);
   
   to
   
   Avoiding 
   
   warning: implicit conversion loses integer precision: 'NSUInteger' (aka 'unsigned long') to 'uint32_t' (aka 'unsigned int')
