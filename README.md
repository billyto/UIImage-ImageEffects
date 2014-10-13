UIImage-ImageEffects
====================

Modified version of Apple's WWDC 2013 UIImage category, change


      NSUInteger radius = floor(inputRadius * 3. * sqrt(2 * M_PI) / 4 + 0.5);
   
to
   
      uint32_t radius = floor(inputRadius * 3. * sqrt(2 * M_PI) / 4 + 0.5);
   
Avoiding a cast warning for implicit 64-bit conversions. 
   
__warning:__ *implicit conversion loses integer precision: 'NSUInteger' (aka 'unsigned long') to 'uint32_t' (aka 'unsigned int')*
