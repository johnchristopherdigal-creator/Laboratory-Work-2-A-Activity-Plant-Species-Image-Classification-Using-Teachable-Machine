# 🌿 Laboratory Work 2-A Activity — Plant Species Image Classification Using Teachable Machine

---

## A. Project Overview

### 📋 Description of the Project
This project focuses on creating an image classification model capable of recognizing **20 different types of Coleus varieties**. Using Google's Teachable Machine, we collected and organized images of various Coleus varieties (genus *Plectranthus scutellarioides*) to train and test the model's accuracy in identifying each unique plant species based on their distinct leaf patterns, colors, and shapes.

---

### 🎯 Purpose of the Image Classification Model
This project uses image classification to distinguish between different Coleus varieties by analyzing their leaf patterns and colors. It demonstrates how **Artificial Intelligence (AI)** can simplify plant identification, support botanical research, and serve as a practical tool for gardeners, botanists, and researchers who need a fast and reliable way to identify plant species.

---

## B. Plant Species Section

<table>
  <tr>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/1._kong_rose.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>1. Kong Rose Coleus</b><br/>
      <i>Plectranthus scutellarioides 'Kong Rose'</i><br/>
      <sub>Large-leafed variety with stunning rose-pink center surrounded by deep green or burgundy edges. Thrives in shaded to partially shaded environments.</sub>
    </td>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/2._Campfire_Coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>2. Campfire Coleus</b><br/>
      <i>Plectranthus scutellarioides 'Campfire'</i><br/>
      <sub>Vibrant orange, red, and yellow leaves resembling flickering flames. Sun-tolerant variety popular for bright outdoor garden beds.</sub>
    </td>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/3._Golden_Dream_Coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>3. Golden Dream Coleus</b><br/>
      <i>Plectranthus scutellarioides 'Golden Dream'</i><br/>
      <sub>Bright golden-yellow leaves with light green edges. Grows best in partial shade and adds a warm sunny tone to garden landscapes.</sub>
    </td>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/4._Rediculous_Coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>4. Rediculous Coleus</b><br/>
      <i>Plectranthus scutellarioides 'Rediculous'</i><br/>
      <sub>Bold, vivid red and pink foliage with contrasting edges. A standout ornamental plant in both indoor and outdoor settings.</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/5._Wicked_Witch_Coleus.png" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>5. Wicked Witch Coleus</b><br/>
      <i>Plectranthus scutellarioides 'Wicked Witch'</i><br/>
      <sub>Deep burgundy to almost black leaves with ruffled, serrated edges. Popular for Halloween-themed or gothic-style gardens.</sub>
    </td>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/6._El_Brighto_Coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>6. El Brighto Coleus</b><br/>
      <i>Plectranthus scutellarioides 'El Brighto'</i><br/>
      <sub>Brilliantly bright multi-colored leaves in shades of yellow, green, and red. Thrives in partially shaded garden spots.</sub>
    </td>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/7._French_Quarter_Coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>7. French Quarter Coleus</b><br/>
      <i>Plectranthus scutellarioides 'French Quarter'</i><br/>
      <sub>Uniquely shaped deeply lobed leaves with rich color combinations of purple, green, and cream. Adds a lush tropical feel.</sub>
    </td>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/8._Trusty_Rusty_Coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>8. Trusty Rusty Coleus</b><br/>
      <i>Plectranthus scutellarioides 'Trusty Rusty'</i><br/>
      <sub>Warm rusty-brown and copper-toned foliage with subtle green undertones. Versatile for natural or rustic garden themes.</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/9._Wizard_Jade_Coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>9. Wizard Jade Coleus</b><br/>
      <i>Plectranthus scutellarioides 'Wizard Jade'</i><br/>
      <sub>Soft jade-green leaves with creamy white centers and delicate pink accents. Part of the easy-to-grow Wizard series.</sub>
    </td>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/10._Black_Dragon_Coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>10. Black Dragon Coleus</b><br/>
      <i>Plectranthus scutellarioides 'Black Dragon'</i><br/>
      <sub>Almost entirely dark maroon to near-black leaves with a velvety texture. Creates bold contrast when paired with lighter plants.</sub>
    </td>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/11._Fishnet_Stockings_Coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>11. Fishnet Stockings Coleus</b><br/>
      <i>Plectranthus scutellarioides 'Fishnet Stockings'</i><br/>
      <sub>Intricate dark veining over light green leaf surface resembling a fishnet pattern. An eye-catching conversation piece in any garden.</sub>
    </td>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/12._Twist_and_Twirl_Coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>12. Twist and Twirl Coleus</b><br/>
      <i>Plectranthus scutellarioides 'Twist and Twirl'</i><br/>
      <sub>Uniquely curled and twisted leaf edges with a mix of red, green, and gold. A whimsical decorative standout in pots and borders.</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/13._Reckles_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>13. Reckless Coleus</b><br/>
      <i>Plectranthus scutellarioides 'Reckless'</i><br/>
      <sub>Bold high-contrast foliage in vivid shades of red and yellow-green. Untamed energetic appearance that adds vibrancy to garden displays.</sub>
    </td>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/14._Chocolate_Covered_Cherry_Coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>14. Chocolate Covered Cherry</b><br/>
      <i>Plectranthus scutellarioides 'Chocolate Covered Cherry'</i><br/>
      <sub>Deep chocolate-brown leaves with bright cherry-red centers. Adds a rich dessert-inspired palette to ornamental gardens.</sub>
    </td>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/15._Stained_Glassworks_Kiwi_Coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>15. Stained Glassworks Kiwi</b><br/>
      <i>Plectranthus scutellarioides 'Stained Glassworks Kiwi'</i><br/>
      <sub>Stunning mosaic of lime green, yellow, and red resembling stained glass art. Sun-tolerant and ideal for bright colorful displays.</sub>
    </td>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/16._Henna_Coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>16. Henna Coleus</b><br/>
      <i>Plectranthus scutellarioides 'Henna'</i><br/>
      <sub>Deeply cut fern-like leaves in warm shades of copper, orange, and brown. Exotic artistic appearance reminiscent of henna art patterns.</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/17._Lime_Coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>17. Lime Coleus</b><br/>
      <i>Plectranthus scutellarioides 'Lime'</i><br/>
      <sub>Bright and cheerful uniform vivid lime-green foliage. Excellent contrast plant when paired with darker or more colorful varieties.</sub>
    </td>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/18._Wizard_Rose_Coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>18. Wizard Rose Coleus</b><br/>
      <i>Plectranthus scutellarioides 'Wizard Rose'</i><br/>
      <sub>Soft rose-pink centers with green-edged leaves. Part of the easy-to-grow Wizard series, well-suited for beginner gardeners.</sub>
    </td>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/19._Burgundy_Wedding_Train_Coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>19. Burgundy Wedding Train</b><br/>
      <i>Plectranthus scutellarioides 'Burgundy Wedding Train'</i><br/>
      <sub>Long trailing burgundy leaves with ruffled edges. Ideal for hanging baskets with a formal sophisticated look for decorative arrangements.</sub>
    </td>
    <td align="center" width="25%">
      <img src="screenshot/plant-species/20._Coleus_Amboinicus_(Cuban_Oregano).jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>20. Cuban Oregano</b><br/>
      <i>Coleus amboinicus</i><br/>
      <sub>Succulent-like herb with thick fleshy aromatic leaves used in cooking and traditional medicine. Strong oregano-like scent used across Southeast Asia.</sub>
    </td>
  </tr>
</table>

---

## C. Model Training Details

| Parameter | Value |
|-----------|-------|
| **Epochs** | 100 |
| **Batch Size** | 16 |
| **Learning Rate** | 0.001 |
| **Number of Images per Class** | 250–786 images |

### Training Settings Screenshot

<p align="center">
  <img src="screenshot/training/training_settings.png" width="700px"/><br/>
  <sub>Teachable Machine Training Configuration — Epochs: 100, Batch Size: 16, Learning Rate: 0.001</sub>
</p>

### Why These Values?
- **Epochs: 100** — Enough iterations to allow the model to fully learn the distinct leaf patterns and colors of all 20 Coleus varieties without underfitting.
- **Batch Size: 16** — A small batch size that provides stable gradient updates and works well with the dataset size.
- **Learning Rate: 0.001** — A standard learning rate that ensures steady convergence without overshooting the optimal weights.

---

## D. Model Evaluation

### 📊 Confusion Matrix

<p align="center">
  <img src="screenshot/evaluation/confusion_matrix.png" width="700px"/><br/>
  <sub>Confusion Matrix — showing predicted vs actual classes across all 20 Coleus varieties</sub>
</p>

### 🎯 Accuracy per Class

<p align="center">
  <img src="screenshot/evaluation/Accuracy_per_class.png" width="700px"/><br/>
  <sub>Accuracy per Class — most classes achieved 1.00 accuracy</sub>
</p>

### ✅ Overall Model Accuracy

<p align="center">
  <img src="screenshot/evaluation/overall_model_accuracy.png" width="700px"/><br/>
  <sub>Overall Model Accuracy and Loss per Epoch</sub>
</p>

| Class | Accuracy | Samples |
|-------|----------|---------|
| Kong Rose | 1.00 | 62 |
| Campfire Coleus | 1.00 | 40 |
| Golden Dream Coleus | 1.00 | 41 |
| Rediculous Coleus | 1.00 | 38 |
| Wicked Witch Coleus | 1.00 | 38 |
| El Brighto Coleus | 1.00 | 42 |
| French Quarter Coleus | 1.00 | 38 |
| Trusty Rusty Coleus | 1.00 | 38 |
| Wizard Jade Coleus | 1.00 | 43 |
| Black Dragon Coleus | 0.97 | 40 |
| Fishnet Stockings Coleus | 1.00 | 44 |
| Twist and Twirl Coleus | 1.00 | 40 |
| Reckless Coleus | 1.00 | 118 |
| Chocolate Covered Cherry | 1.00 | 45 |
| Stained Glassworks Kiwi | 1.00 | 41 |
| Henna Coleus | 1.00 | 42 |
| Lime Coleus | 1.00 | 57 |
| Wizard Rose Coleus | 1.00 | 43 |
| Burgundy Wedding Train | 0.99 | 68 |
| Coleus amboinicus | 1.00 | 59 |

---

## E. Model Testing

> 18 testing screenshots were performed using the Preview section of Teachable Machine, testing each of the 20 Coleus varieties with real images.

<table>
  <tr>
    <td align="center" width="50%">
      <img src="screenshot/testing/2_campfire_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 1 — Campfire Coleus</b><br/>
      <img src="screenshot/testing/2_campfire_coleus_testing.png" width="380px"/><br/>
      <sub>✅ Predicted: Campfire Coleus | Confidence: 100%</sub>
    </td>
    <td align="center" width="50%">
      <img src="screenshot/testing/3_golden_dream_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 2 — Golden Dream Coleus</b><br/>
      <img src="screenshot/testing/3_golden_dream_coleus_testing.png" width="380px"/><br/>
      <sub>✅ Predicted: Golden Dream Coleus | Confidence: 100%</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="screenshot/testing/5_wicked_witch_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 3 — Wicked Witch Coleus</b><br/>
      <img src="screenshot/testing/5_wicked_witch_coleus_testing.png" width="380px"/><br/>
      <sub>✅ Predicted: Wicked Witch Coleus | Confidence: 100%</sub>
    </td>
    <td align="center" width="50%">
      <img src="screenshot/testing/6_el_brighto_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 4 — El Brighto Coleus</b><br/>
      <img src="screenshot/testing/6_el_brighto_coleus_testing.jpg" width="380px"/><br/>
      <sub>✅ Predicted: El Brighto Coleus | Confidence: 100%</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="screenshot/testing/7_french_quarter_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 5 — French Quarter Coleus</b><br/>
      <img src="screenshot/testing/7_french_quarter_coleus_testing_part2.jpg" width="380px"/><br/>
      <sub>✅ Predicted: French Quarter Coleus | Confidence: 95%</sub>
    </td>
    <td align="center" width="50%">
      <img src="screenshot/testing/8_trusty_rusty_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 6 — Trusty Rusty Coleus</b><br/>
      <img src="screenshot/testing/8_trusty_rusty_coleus_testing_part2.jpg" width="380px"/><br/>
      <sub>✅ Predicted: Trusty Rusty Coleus | Confidence: 100%</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="screenshot/testing/9_wizard_jade_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 7 — Wizard Jade Coleus</b><br/>
      <img src="screenshot/testing/9_wizard_jade_coleus_testing_part2.jpg" width="380px"/><br/>
      <sub>✅ Predicted: Wizard Jade Coleus | Confidence: 100%</sub>
    </td>
    <td align="center" width="50%">
      <img src="screenshot/testing/10_black_dragon_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 8 — Black Dragon Coleus</b><br/>
      <img src="screenshot/testing/10_black_dragon_coleus_testing_part2.jpg" width="380px"/><br/>
      <sub>✅ Predicted: Black Dragon Coleus | Confidence: 100%</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="screenshot/testing/11_fishnet_stockings_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 9 — Fishnet Stockings Coleus</b><br/>
      <img src="screenshot/testing/11_fishnet_stockings_coleus_testing_part2.jpg" width="380px"/><br/>
      <sub>✅ Predicted: Fishnet Stockings Coleus | Confidence: 100%</sub>
    </td>
    <td align="center" width="50%">
      <img src="screenshot/testing/12_twist_and_twirl_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 10 — Twist and Twirl Coleus</b><br/>
      <img src="screenshot/testing/12_twist_and_twirl_coleus_testing_part2.jpg" width="380px"/><br/>
      <sub>✅ Predicted: Twist and Twirl Coleus | Confidence: 100%</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="screenshot/testing/13_reckles_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 11 — Reckless Coleus</b><br/>
      <img src="screenshot/testing/13_reckles_coleus_testing_part2.jpg" width="380px"/><br/>
      <sub>✅ Predicted: Reckless Coleus | Confidence: 100%</sub>
    </td>
    <td align="center" width="50%">
      <img src="screenshot/testing/14_chocolate_covered_cherry_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 12 — Chocolate Covered Cherry</b><br/>
      <img src="screenshot/testing/14_chocolate_covered_cherry_coleus_testing_part2.jpg" width="380px"/><br/>
      <sub>✅ Predicted: Chocolate Covered Cherry | Confidence: 99%</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="screenshot/testing/15_Stained_Glassworks_Kiwi_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 13 — Stained Glassworks Kiwi</b><br/>
      <img src="screenshot/testing/15_Stained_Glassworks_Kiwi_coleus_testing_part2.jpg" width="380px"/><br/>
      <sub>✅ Predicted: Stained Glassworks Kiwi | Confidence: 100%</sub>
    </td>
    <td align="center" width="50%">
      <img src="screenshot/testing/16_Henna_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 14 — Henna Coleus</b><br/>
      <img src="screenshot/testing/16_Henna_coleus_testing_part2.jpg" width="380px"/><br/>
      <sub>✅ Predicted: Henna Coleus | Confidence: 99%</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="screenshot/testing/17_lime_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 15 — Lime Coleus</b><br/>
      <img src="screenshot/testing/17_lime_coleus_testing_part2.jpg" width="380px"/><br/>
      <sub>✅ Predicted: Lime Coleus | Confidence: 100%</sub>
    </td>
    <td align="center" width="50%">
      <img src="screenshot/testing/18_wizard_rose_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 16 — Wizard Rose Coleus</b><br/>
      <img src="screenshot/testing/18_wizard_rose_coleus_testing_part2.jpg" width="380px"/><br/>
      <sub>✅ Predicted: Wizard Rose Coleus | Confidence: 100%</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="screenshot/testing/19_Burgundy_Wedding_Train_coleus.jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 17 — Burgundy Wedding Train</b><br/>
      <img src="screenshot/testing/19_Burgundy_Wedding_Train_coleus_testing_part2.jpg" width="380px"/><br/>
      <sub>✅ Predicted: Burgundy Wedding Train | Confidence: 100%</sub>
    </td>
    <td align="center" width="50%">
      <img src="screenshot/testing/20_Coleus_amboinicus_(Cuban_Oregano).jpg" width="200px" height="200px" style="object-fit:cover;border-radius:10px;"/><br/>
      <b>Test 18 — Cuban Oregano</b><br/>
      <img src="screenshot/testing/20_Coleus_amboinicus__Cuban_Oregano__testing_part2.jpg" width="380px"/><br/>
      <sub>✅ Predicted: Coleus amboinicus | Confidence: 100%</sub>
    </td>
  </tr>
</table>
