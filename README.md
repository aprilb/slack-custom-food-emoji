# slack-custom-food-emoji

Uploads Glitch food and drink icons as custom emoji to a Slack team.

## usage

- Sign into your Slack workspace in Google Chrome.
- Run the following commands in your terminal

```
# Clone the food emoji project to slack-custom-food-emoji
git clone git@github.com:bertrandom/slack-custom-food-emoji.git
# Change directory to 
cd slack-custom-food-emoji
# Install dependencies
npm install
# Downloads the glitch-assets-parser repo to ./glitch-assets-parser
git clone git@github.com:bertrandom/glitch-assets-parser.git
# Uploads the emoji to your workspace
node ./index.js [workspace name]
```

Where [workspace name] is the prefix to your Slack domain. For example if you access slack using https://example.slack.com, you would use `node ./index.js example`

![:abbasid-ribs:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/abbasid_ribs/abbasid_ribs__x1_iconic_png_1354829688.png)
![:apple:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/apple/apple__x1_iconic_png_1354829396.png)
![:applejack:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/applejack/applejack__x1_iconic_png_1354830825.png)
![:awesome-stew:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/awesome_stew/awesome_stew__x1_iconic_png_1354829702.png)
![:bacon:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/bacon/bacon__x1_iconic_png_1354829444.png)
![:banana:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/banana/banana__x1_iconic_png_1354829403.png)
![:banana-no-names:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/banana_no_names/banana_no_names__x1_iconic_png_1354830815.png)
![:basic-omelet:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/basic_omelet/basic_omelet__x1_iconic_png_1354829706.png)
![:beer:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/beer/beer__x1_iconic_png_1354829708.png)
![:berry-bowl:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/berry_bowl/berry_bowl__x1_iconic_png_1354830844.png)
![:best-bean-dip:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/best_bean_dip/best_bean_dip__x1_iconic_png_1354829711.png)
![:big-salad:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/big_salad/big_salad__x1_iconic_png_1354829714.png)
![:birch-candy:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/birch_candy/birch_candy__x1_iconic_png_1354836540.png)
![:birch-syrup:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/birch_syrup/birch_syrup__x1_iconic_png_1354829716.png)
![:blue-sno-cone:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/sno_cone_blue/sno_cone_blue__x1_iconic_png_1354830753.png)
![:bubble-and-squeak:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/bubble_and_squeak/bubble_and_squeak__x1_iconic_png_1354830829.png)
![:bubble-tea:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/bubble_tea/bubble_tea__x1_iconic_png_1354829726.png)
![:bun:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/bun/bun__x1_iconic_png_1354829685.png)
![:bunch-of-grapes:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/bunch_of_grapes/bunch_of_grapes__x1_iconic_png_1354829729.png)
![:butterfly-butter:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/butterfly_butter/butterfly_butter__x1_iconic_png_1354829519.png)
![:butterfly-milk:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/milk_butterfly/milk_butterfly__x1_iconic_png_1354829507.png)
![:carobish-treats:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/carobish_treats/carobish_treats__x1_iconic_png_1354836545.png)
![:carrot-margarita:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/carrot_margarita/carrot_margarita__x1_iconic_png_1354829742.png)
![:cedar-plank-salmon:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/cedar_plank_salmon/cedar_plank_salmon__x1_iconic_png_1354829745.png)
![:cheese:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/cheese/cheese__x1_iconic_png_1354829748.png)
![:cheese-plate:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/cheese_plate/cheese_plate__x1_iconic_png_1354829751.png)
![:cheezy-sammich:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/cheezy_sammich/cheezy_sammich__x1_iconic_png_1354830841.png)
![:cheezy-sauce:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/cheezy_sauce/cheezy_sauce__x1_iconic_png_1354829753.png)
![:chillybusting-chili:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/chillybusting_chili/chillybusting_chili__x1_iconic_png_1354829759.png)
![:choice-crudites:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/choice_crudites/choice_crudites__x1_iconic_png_1354829762.png)
![:cloud-11-smoothie:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/cloud_11_smoothie/cloud_11_smoothie__x1_iconic_png_1354829690.png)
![:cloudberry:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/cloudberry/cloudberry__x1_iconic_png_1354829768.png)
![:cloudberry-daiquiri:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/cloudberry_daiquiri/cloudberry_daiquiri__x1_iconic_png_1354829771.png)
![:cloudberry-jam:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/cloudberry_jam/cloudberry_jam__x1_iconic_png_1354829776.png)
![:coffee:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/coffee/coffee__x1_iconic_png_1354829779.png)
![:cold-taco:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/cold_taco/cold_taco__x1_iconic_png_1354830854.png)
![:common-crudites:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/common_crudites/common_crudites__x1_iconic_png_1354829782.png)
![:corn-off-the-cob:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/corn_off_the_cob/corn_off_the_cob__x1_iconic_png_1354830806.png)
![:corn-syrup-squares:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/corn_syrup_squares/corn_syrup_squares__x1_iconic_png_1354836543.png)
![:corny-fritter:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/corny_fritter/corny_fritter__x1_iconic_png_1354830804.png)
![:cosma-politan:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/cosmapolitan/cosmapolitan__x1_iconic_png_1354829788.png)
![:crabato-juice:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/crabato_juice/crabato_juice__x1_iconic_png_1354831176.png)
![:creamy-catsup:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/creamy_catsup/creamy_catsup__x1_iconic_png_1354829790.png)
![:creamy-martini:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/creamy_martini/creamy_martini__x1_iconic_png_1354829793.png)
![:cup-of-water:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/cup_of_water/cup_of_water__x1_iconic_png_1354833111.png)
![:death-to-veg:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/death_to_veg/death_to_veg__x1_iconic_png_1354840586.png)
![:deluxe-sammich:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/deluxe_sammich/deluxe_sammich__x1_iconic_png_1354829800.png)
![:desssert-rub:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/desssert_rub/desssert_rub__x1_iconic_png_1354840578.png)
![:divine-crepes:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/divine_crepes/divine_crepes__x1_iconic_png_1354829802.png)
![:earthshaker:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/earthshaker/earthshaker__x1_iconic_png_1354829805.png)
![:eggy-scramble:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/eggy_scramble/eggy_scramble__x1_iconic_png_1354830799.png)
![:exotic-fruit-salad:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/exotic_fruit_salad/exotic_fruit_salad__x1_iconic_png_1354830859.png)
![:exotic-juice:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/exotic_juice/exotic_juice__x1_iconic_png_1354829808.png)
![:expensive-grilled-cheese:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/expensive_grilled_cheese/expensive_grilled_cheese__x1_iconic_png_1354829810.png)
![:face-smelter:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/face_smelter/face_smelter__x1_iconic_png_1354839793.png)
![:flaming-humbaba:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/flaming_humbaba/flaming_humbaba__x1_iconic_png_1354829817.png)
![:flour:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/flour/flour__x1_iconic_png_1354829828.png)
![:flummery:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/flummery/flummery__x1_iconic_png_1354830832.png)
![:fortifying-gruel:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/fortifying_gruel/fortifying_gruel__x1_iconic_png_1354829830.png)
![:fried-egg:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/fried_egg/fried_egg__x1_iconic_png_1354830100.png)
![:fried-noodles:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/fried_noodles/fried_noodles__x1_iconic_png_1354830818.png)
![:fried-rice:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/fried_rice/fried_rice__x1_iconic_png_1354829839.png)
![:frog-in-a-hole:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/frog_in_a_hole/frog_in_a_hole__x1_iconic_png_1354830827.png)
![:fruit-salad:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/fruit_salad/fruit_salad__x1_iconic_png_1354829842.png)
![:fruity-juice:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/fruity_juice/fruity_juice__x1_iconic_png_1354829844.png)
![:gammas-pancakes:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/gammas_pancakes/gammas_pancakes__x1_iconic_png_1354829847.png)
![:glitchepoix:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/glitchepoix/glitchepoix__x1_iconic_png_1354840634.png)
![:greasy-frybread:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/greasy_frybread/greasy_frybread__x1_iconic_png_1354830839.png)
![:green:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/green/green__x1_iconic_png_1354840603.png)
![:green-eggs:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/green_eggs/green_eggs__x1_iconic_png_1354830822.png)
![:green-sno-cone:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/sno_cone_green/sno_cone_green__x1_iconic_png_1354830756.png)
![:grilled-cheese:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/grilled_cheese/grilled_cheese__x1_iconic_png_1354829862.png)
![:gurly-drink:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/gurly_drink/gurly_drink__x1_iconic_png_1354829865.png)
![:hash:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/hash/hash__x1_iconic_png_1354829870.png)
![:hearty-groddle-sammich:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/hearty_groddle_sammich/hearty_groddle_sammich__x1_iconic_png_1354829872.png)
![:hearty-omelet:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/hearty_omelet/hearty_omelet__x1_iconic_png_1354829876.png)
![:heston-mash:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/heston_mash/heston_mash__x1_iconic_png_1354840617.png)
![:honey:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/honey/honey__x1_iconic_png_1354829878.png)
![:hooch:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/hooch/hooch__x1_iconic_png_1354829881.png)
![:hot-n-fizzy-sauce:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/hot_n_fizzy_sauce/hot_n_fizzy_sauce__x1_iconic_png_1354829885.png)
![:hot-potatoes:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/hot_potatoes/hot_potatoes__x1_iconic_png_1354840612.png)
![:hototot-rub:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/hototot_rub/hototot_rub__x1_iconic_png_1354840573.png)
![:hungry-nachos:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/hungry_nachos/hungry_nachos__x1_iconic_png_1354840629.png)
![:ixstyle-braised-meat:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/ixstyle_braised_meat/ixstyle_braised_meat__x1_iconic_png_1354829692.png)
![:juicy-carpaccio:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/juicy_carpaccio/juicy_carpaccio__x1_iconic_png_1354829894.png)
![:kind-breakfurst-burrito:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/kind_breakfurst_burrito/kind_breakfurst_burrito__x1_iconic_png_1354840594.png)
![:king-of-condiments:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/kings_of_condiments/kings_of_condiments__x1_iconic_png_1354840568.png)
![:lazy-salad:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/lazy_salad/lazy_salad__x1_iconic_png_1354830846.png)
![:legumes-abbassidienne:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/legumes_parisienne/legumes_parisienne__x1_iconic_png_1354840571.png)
![:lemburger:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/lemburger/lemburger__x1_iconic_png_1354829695.png)
![:lemon:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/lemon/lemon__x1_iconic_png_1354829897.png)
![:lemon-juice:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/lemon_juice/lemon_juice__x1_iconic_png_1354829899.png)
![:lotsa-lox:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/lotsa_lox/lotsa_lox__x1_iconic_png_1354830851.png)
![:luxury-tortellini:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/luxury_tortellini/luxury_tortellini__x1_iconic_png_1354840622.png)
![:mabbish-coffee:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/mabbish_coffee/mabbish_coffee__x1_iconic_png_1354829697.png)
![:maburger-royale:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/maburger_royale/maburger_royale__x1_iconic_png_1354840610.png)
![:mangosteen:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/mangosteen/mangosteen__x1_iconic_png_1354829464.png)
![:meat-gumbo:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/meat_gumbo/meat_gumbo__x1_iconic_png_1354829905.png)
![:meat-tetrazzini:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/meat_tetrazzini/meat_tetrazzini__x1_iconic_png_1354829907.png)
![:mega-healthy-veggie-juice:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/mega_healthy_veggie_juice/mega_healthy_veggie_juice__x1_iconic_png_1354829910.png)
![:messy-fry-up:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/messy_fry_up/messy_fry_up__x1_iconic_png_1354830820.png)
![:mexicali-eggs:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/mexicali_eggs/mexicali_eggs__x1_iconic_png_1354830801.png)
![:mild-sauce:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/mild_sauce/mild_sauce__x1_iconic_png_1354829912.png)
![:mushroom:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/mushroom/mushroom__x1_iconic_png_1354829915.png)
![:naraka-flame-rub:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/naraka_flame_rub/naraka_flame_rub__x1_iconic_png_1354840580.png)
![:oats:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/oats/oats__x1_iconic_png_1354829923.png)
![:oaty-cake:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/oaty_cake/oaty_cake__x1_iconic_png_1354830808.png)
![:obvious-panini:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/obvious_panini/obvious_panini__x1_iconic_png_1354829928.png)
![:oily-dressing:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/oily_dressing/oily_dressing__x1_iconic_png_1354829931.png)
![:olive-oil:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/olive_oil/olive_oil__x1_iconic_png_1354829936.png)
![:onion-ring:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/onion_rings/onion_rings__x1_iconic_png_1354840636.png)
![:onion-sauce:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/onion_sauce/onion_sauce__x1_iconic_png_1354829941.png)
![:orange:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/orange/orange__x1_iconic_png_1354829400.png)
![:orange-juice:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/orange_juice/orange_juice__x1_iconic_png_1354829944.png)
![:orange-sno-cone:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/sno_cone_orange/sno_cone_orange__x1_iconic_png_1354830759.png)
![:pad-tii:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/pad_tii/pad_tii__x1_iconic_png_1354840624.png)
![:pi:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/pi/pi__x1_iconic_png_1354839579.png)
![:pickle:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/pickle/pickle__x1_iconic_png_1354829951.png)
![:pineapple:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/pineapple/pineapple__x1_iconic_png_1354829957.png)
![:pineapple-upside-down-pizza:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/papl_upside_down_pizza/papl_upside_down_pizza__x1_iconic_png_1354829946.png)
![:plain-noodles:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/plain_noodles/plain_noodles__x1_iconic_png_1354829964.png)
![:plum:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/plum/plum__x1_iconic_png_1354829973.png)
![:pocket-salmon:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/salmon/salmon__x1_iconic_png_1354829990.png)
![:potato-patty:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/potato_patty/potato_patty__x1_iconic_png_1354830837.png)
![:potcorn:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/potcorn/potcorn__x1_iconic_png_1354840615.png)
![:potians-feast:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/potians_feast/potians_feast__x1_iconic_png_1354840631.png)
![:pottine:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/pottine/pottine__x1_iconic_png_1354840608.png)
![:precious-potato-salad:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/precious_potato_salad/precious_potato_salad__x1_iconic_png_1354840619.png)
![:proper-rice:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/proper_rice/proper_rice__x1_iconic_png_1354829978.png)
![:pumpkin-ale:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/pumpkin_ale/pumpkin_ale__x1_iconic_png_1354836548.png)
![:pumpkin-pie:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/pumpkin_pie/pumpkin_pie__x1_iconic_png_1354836550.png)
![:pungent-sunrise:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/pungent_sunrise/pungent_sunrise__x1_iconic_png_1354829980.png)
![:purple-sno-cone:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/sno_cone_purple/sno_cone_purple__x1_iconic_png_1354830764.png)
![:rainbo-sno-cone:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/sno_cone_rainbow/sno_cone_rainbow__x1_iconic_png_1354840518.png)
![:red:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/red/red__x1_iconic_png_1354840598.png)
![:red-sno-cone:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/sno_cone_red/sno_cone_red__x1_iconic_png_1354830762.png)
![:rich-tagine:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/rich_tagine/rich_tagine__x1_iconic_png_1354829985.png)
![:roasted-pepitas:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/pepitas/pepitas__x1_iconic_png_1354836537.png)
![:roux:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/roux/roux__x1_iconic_png_1354840596.png)
![:salmon-jaella:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/salmon_jaella/salmon_jaella__x1_iconic_png_1354840591.png)
![:sammich:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/sammich/sammich__x1_iconic_png_1354829993.png)
![:savory-smoothie:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/savory_smoothie/savory_smoothie__x1_iconic_png_1354829997.png)
![:scrumptious-frittata:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/scrumptious_frittata/scrumptious_frittata__x1_iconic_png_1354830001.png)
![:secret-sauce:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/secret_sauce/secret_sauce__x1_iconic_png_1354830003.png)
![:sesame-oil:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/sesame_oil/sesame_oil__x1_iconic_png_1354830008.png)
![:simple-bbq:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/simple_bbq/simple_bbq__x1_iconic_png_1354830010.png)
![:simple-slaw:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/simple_slaw/simple_slaw__x1_iconic_png_1354830013.png)
![:slow-gin-fizz:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/slow_gin_fizz/slow_gin_fizz__x1_iconic_png_1354830016.png)
![:snack-pack:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/snack_pack/snack_pack__x1_iconic_png_1354830849.png)
![:spicy-grog:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/spicy_grog/spicy_grog__x1_iconic_png_1354830019.png)
![:spicy-quesadilla:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/spicy_quesadilla/spicy_quesadilla__x1_iconic_png_1354830021.png)
![:spinach-salad:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/spinach_salad/spinach_salad__x1_iconic_png_1354830856.png)
![:stinky-cheese:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/cheese_stinky/cheese_stinky__x1_iconic_png_1354829497.png)
![:stock-sauce:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/stock_sauce/stock_sauce__x1_iconic_png_1354840601.png)
![:strawberry:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/strawberry/strawberry__x1_iconic_png_1354830026.png)
![:super-veggie-kebabs:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/super_veggie_kebabs/super_veggie_kebabs__x1_iconic_png_1354830029.png)
![:swank-zucchini-loaf:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/swank_zucchini_loaf/swank_zucchini_loaf__x1_iconic_png_1354840626.png)
![:sweet-n-sour-sauce:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/sweet_n_sour_sauce/sweet_n_sour_sauce__x1_iconic_png_1354830031.png)
![:swing-batter:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/swing_batter/swing_batter__x1_iconic_png_1354840575.png)
![:tangy-noodles:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/tangy_noodles/tangy_noodles__x1_iconic_png_1354830834.png)
![:tangy-sauce:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/tangy_sauce/tangy_sauce__x1_iconic_png_1354830034.png)
![:tasty-pasta:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/tasty_pasta/tasty_pasta__x1_iconic_png_1354830038.png)
![:tooberry-shake:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/tooberry_shake/tooberry_shake__x1_iconic_png_1354830046.png)
![:tortilla:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/tortilla/tortilla__x1_iconic_png_1354830048.png)
![:trump-rub:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/trump_rub/trump_rub__x1_iconic_png_1354840583.png)
![:urfu:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/urfu/urfu__x1_iconic_png_1354840588.png)
![:vegmageddon:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/vegmageddon/vegmageddon__x1_iconic_png_1354840605.png)
![:very-stinky-cheese:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/cheese_very_stinky/cheese_very_stinky__x1_iconic_png_1354829499.png)
![:very-very-stinky-cheese:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/cheese_very_very_stinky/cheese_very_very_stinky__x1_iconic_png_1354829502.png)
![:waffles:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/waffles/waffles__x1_iconic_png_1354830054.png)
![:wavy-gravy:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/wavy_gravy/wavy_gravy__x1_iconic_png_1354830056.png)
![:whortleberry:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/whortleberry/whortleberry__x1_iconic_png_1354830059.png)
![:whortleberry-jelly:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/whortleberry_jelly/whortleberry_jelly__x1_iconic_png_1354830062.png)
![:wicked-bolognese-sauce:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/wicked_bolognese_sauce/wicked_bolognese_sauce__x1_iconic_png_1354830065.png)
![:wine-of-the-dead:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/wine_of_the_dead/wine_of_the_dead__x1_iconic_png_1354830988.png)
![:yummy-gruel:](https://raw.githubusercontent.com/bertrandom/glitch-assets-parser/master/glitch-assets/yummy_gruel/yummy_gruel__x1_iconic_png_1354830068.png)

## license

MIT
