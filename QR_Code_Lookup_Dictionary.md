# QR Code Lookup Dictionary

## Plant Catalog - URL to Content Mapping

This file contains pre-cached content for QR code URLs to eliminate the need for web requests during testing. Your QR code reader can simply match URLs to this dictionary for instant results.

---

## Implementation Instructions for C#

```csharp
// Example C# Dictionary Implementation
public static Dictionary<string, PlantInfo> QRCodeLookup = new Dictionary<string, PlantInfo>
{
    ["https://henryvu27.github.io/plants/TOM-BS-001"] = new PlantInfo { /* tomato data */ },
    ["https://henryvu27.github.io/plants/BEP-CYW-003"] = new PlantInfo { /* bell pepper data */ },
    // ... etc
};

public class PlantInfo
{
    public string PlantId { get; set; }
    public string CommonName { get; set; }
    public string ScientificName { get; set; }
    public string Variety { get; set; }
    public string Description { get; set; }
    public PlantCare Care { get; set; }
    public List<string> Images { get; set; }
    public PlantCharacteristics Characteristics { get; set; }
}
```

---

## URL: https://henryvu27.github.io/plants/TOM-BS-001

### Tomato - Beefsteak Variety

**Plant ID:** TOM-BS-001

**Scientific Name:** Solanum lycopersicum

**Common Name:** Tomato

**Variety:** Beefsteak

**Description:** A classic, large, and juicy tomato variety perfect for slicing for sandwiches and burgers. Known for its meaty texture and balanced sweet-acid flavor. The beefsteak variety produces extra-large fruits, often weighing 1-2 pounds each, with excellent disease resistance.

**Care Instructions:**
- **Sunlight:** Full sun (6-8 hours daily)
- **Water:** Deep, consistent watering - 1-2 inches per week
- **Soil:** Well-draining, fertile soil with pH 6.0-6.8
- **Temperature:** 65-75°F optimal growing temperature
- **Support:** Requires sturdy staking or caging due to large fruit size
- **Fertilizer:** Regular feeding with tomato-specific fertilizer

**Planting Information:**
- **Spacing:** 24-36 inches apart
- **Depth:** Plant deep, burying 2/3 of stem
- **Season:** Start indoors 6-8 weeks before last frost
- **Harvest:** 75-85 days from transplant

**Characteristics:**
- **Growth Habit:** Indeterminate (continues growing and producing)
- **Fruit Size:** 1-2 pounds per tomato
- **Color:** Deep red when ripe
- **Flavor Profile:** Rich, balanced sweet-acid taste
- **Disease Resistance:** Resistant to common tomato diseases

**Growing Tips:**
- Remove suckers for better fruit development
- Mulch around plants to retain moisture
- Provide afternoon shade in very hot climates
- Harvest when fruits show first sign of color change

**Images Available:**
- TOM-BS-001-fruit.jpg (ripe beefsteak tomato)
- TOM-BS-001-plant.jpg (full plant with support)
- TOM-BS-001-flower.jpg (yellow tomato flowers)

---

## URL: https://henryvu27.github.io/plants/BEP-CYW-003

### Bell Pepper - California Wonder Variety

**Plant ID:** BEP-CYW-003

**Scientific Name:** Capsicum annuum

**Common Name:** Bell Pepper

**Variety:** California Wonder

**Description:** A classic sweet bell pepper that starts green and ripens to a vibrant red. Features a thick wall, making it great for stuffing or eating fresh. The California Wonder variety is known for its reliability, disease resistance, and excellent flavor development as it ripens from green to red.

**Care Instructions:**
- **Sunlight:** Full sun (6-8 hours daily)
- **Water:** Consistent moisture, avoid waterlogging
- **Soil:** Well-draining, fertile soil with pH 6.0-7.0
- **Temperature:** 70-85°F optimal, sensitive to cold
- **Support:** May need support when heavily loaded with fruit
- **Fertilizer:** Balanced fertilizer, avoid excess nitrogen

**Planting Information:**
- **Spacing:** 18-24 inches apart
- **Depth:** Same depth as root ball
- **Season:** Start indoors 8-10 weeks before last frost
- **Harvest:** 70-75 days from transplant

**Characteristics:**
- **Growth Habit:** Compact bush, 24-30 inches tall
- **Fruit Size:** 3-4 inches wide, 4-5 inches long
- **Color Progression:** Green → Red when fully ripe
- **Wall Thickness:** Very thick, excellent for stuffing
- **Flavor:** Sweet, crisp texture

**Growing Tips:**
- Harvest green peppers early for continued production
- Allow some peppers to ripen to red for sweetest flavor
- Protect from strong winds that can break branches
- Side-dress with compost mid-season

**Images Available:**
- BEP-CYW-003-fruit.jpg (red ripe bell pepper)
- BEP-CYW-003-plant.jpg (pepper plant with fruits)
- BEP-CYW-003-flower.jpg (small white pepper flowers)

---

## URL: https://henryvu27.github.io/plants/OKR-CG-002

### Okra - Clemson Spineless Variety

**Plant ID:** OKR-CG-002

**Scientific Name:** Abelmoschus esculentus

**Common Name:** Okra

**Variety:** Clemson Spineless

**Description:** A popular, high-yielding variety that produces dark green, spineless pods. A staple in Southern cuisine, great for frying, grilling, or in gumbos. The Clemson Spineless variety is prized for its tender pods that remain flavorful even when larger than typical harvest size.

**Care Instructions:**
- **Sunlight:** Full sun (6-8 hours daily)
- **Water:** Moderate water, drought tolerant once established
- **Soil:** Well-draining soil, tolerates poor soils, pH 6.0-7.5
- **Temperature:** Heat-loving, 75-85°F optimal
- **Support:** Generally self-supporting
- **Fertilizer:** Light feeding, avoid excess nitrogen

**Planting Information:**
- **Spacing:** 12-18 inches apart
- **Depth:** 1/2 to 1 inch deep
- **Season:** Direct sow after soil warms to 65°F
- **Harvest:** 50-65 days from seed

**Characteristics:**
- **Growth Habit:** Upright, bushy, 4-6 feet tall
- **Pod Size:** 3-5 inches long when harvested
- **Color:** Dark green pods
- **Texture:** Tender, spineless (no prickly hairs)
- **Productivity:** High yielding, continuous harvest

**Growing Tips:**
- Harvest pods when 3-4 inches long for best tenderness
- Pick regularly to encourage continued production
- Wear long sleeves when harvesting (plant has fine hairs)
- Excellent heat and drought tolerance

**Images Available:**
- OKR-CG-002-fruit.jpg (green okra pods)
- OKR-CG-002-plant.jpg (tall okra plant)
- OKR-CG-002-flower.jpg (beautiful hibiscus-like flower)

---

## URL: https://henryvu27.github.io/plants/CUC-MN-004

### Cucumber - Marketmore 76 Variety

**Plant ID:** CUC-MN-004

**Scientific Name:** Cucumis sativus

**Common Name:** Cucumber

**Variety:** Marketmore 76

**Description:** A popular slicing cucumber known for its productivity and disease resistance. Produces straight, dark green, 8-9 inch fruits. The Marketmore 76 variety is excellent for fresh eating and maintains good quality even in hot weather conditions.

**Care Instructions:**
- **Sunlight:** Full sun (6-8 hours daily)
- **Water:** Consistent, deep watering - 1 inch per week
- **Soil:** Rich, well-draining soil with pH 6.0-7.0
- **Temperature:** 70-85°F optimal, cold sensitive
- **Support:** Benefits from trellising for space efficiency
- **Fertilizer:** Regular feeding with balanced fertilizer

**Planting Information:**
- **Spacing:** 36 inches apart (or 12" if trellised)
- **Depth:** 1/2 to 1 inch deep
- **Season:** Direct sow after last frost when soil is warm
- **Harvest:** 55-65 days from seed

**Characteristics:**
- **Growth Habit:** Vining, spreads 6-8 feet
- **Fruit Size:** 8-9 inches long, 2-3 inches diameter
- **Color:** Dark green with light stripes
- **Texture:** Crisp, juicy, minimal bitterness
- **Disease Resistance:** Excellent resistance to common cucumber diseases

**Growing Tips:**
- Harvest cucumbers when 6-8 inches for best flavor
- Pick regularly to encourage continued production
- Provide consistent moisture to prevent bitter taste
- Mulch to retain soil moisture and suppress weeds

**Images Available:**
- CUC-MN-004-fruit.jpg (fresh slicing cucumber)
- CUC-MN-004-plant.jpg (cucumber vine with fruits)
- CUC-MN-004-flower.jpg (yellow cucumber flowers)

---

## URL: https://henryvu27.github.io/plants/ZUC-BDN-005

### Zucchini - Black Beauty Variety

**Plant ID:** ZUC-BDN-005

**Scientific Name:** Cucurbita pepo

**Common Name:** Zucchini

**Variety:** Black Beauty

**Description:** A prolific summer squash with glossy, dark green skin. Best harvested when young and tender for the best flavor and texture. The Black Beauty variety is known for its compact plant habit and continuous production throughout the growing season.

**Care Instructions:**
- **Sunlight:** Full sun (6-8 hours daily)
- **Water:** Deep, consistent watering - avoid wetting leaves
- **Soil:** Rich, well-draining soil with pH 6.0-7.5
- **Temperature:** 65-75°F optimal growing temperature
- **Support:** Generally self-supporting, but large plants may sprawl
- **Fertilizer:** Heavy feeder, benefits from compost and regular fertilizing

**Planting Information:**
- **Spacing:** 36-48 inches apart
- **Depth:** 1 inch deep
- **Season:** Direct sow after last frost when soil is warm
- **Harvest:** 50-55 days from seed

**Characteristics:**
- **Growth Habit:** Bush type, compact but can spread 3-4 feet
- **Fruit Size:** Harvest at 6-8 inches for best quality
- **Color:** Dark green, almost black skin
- **Texture:** Tender when young, mild flavor
- **Productivity:** Very prolific, harvest daily in peak season

**Growing Tips:**
- Harvest zucchini when 6-8 inches long for tender texture
- Check plants daily during peak production
- Large leaves may need support in windy areas
- Excellent for grilling, baking, and fresh eating

**Images Available:**
- ZUC-BDN-005-fruit.jpg (fresh dark green zucchini)
- ZUC-BDN-005-plant.jpg (zucchini plant with large leaves)
- ZUC-BDN-005-flower.jpg (large yellow squash blossoms)

---

## Quick Reference URL List

For rapid QR code matching:

```
TOM-BS-001 → https://henryvu27.github.io/plants/TOM-BS-001
BEP-CYW-003 → https://henryvu27.github.io/plants/BEP-CYW-003  
OKR-CG-002 → https://henryvu27.github.io/plants/OKR-CG-002
CUC-MN-004 → https://henryvu27.github.io/plants/CUC-MN-004
ZUC-BDN-005 → https://henryvu27.github.io/plants/ZUC-BDN-005
```

---

## C# Implementation Example

```csharp
public class QRCodeService
{
    private static readonly Dictionary<string, PlantData> _plantDatabase = 
        LoadPlantDatabase(); // Load from this markdown file
    
    public PlantData ProcessQRCode(string qrCodeContent)
    {
        // QR code reader returns just the URL
        string url = qrCodeContent.Trim();
        
        // Look up in our dictionary instead of making web request
        if (_plantDatabase.TryGetValue(url, out PlantData plantInfo))
        {
            return plantInfo;
        }
        
        // Fallback if URL not found
        return new PlantData { Error = "Plant information not found" };
    }
    
    private static Dictionary<string, PlantData> LoadPlantDatabase()
    {
        // Parse this markdown file into dictionary
        // or load from JSON/XML version of this data
        return new Dictionary<string, PlantData>();
    }
}
```

---

## Benefits of This Approach

1. **🚀 Speed**: Instant lookup vs web request latency
2. **📱 Offline**: Works without internet connection  
3. **🧪 Testing**: Consistent, reliable test data
4. **💰 Cost**: No web traffic/API costs during development
5. **🔄 Version Control**: Plant data versioned with your code
6. **🛠️ Flexibility**: Easy to add test scenarios and edge cases

## Usage Notes

- Update this file when plant information changes
- Consider generating this file automatically from your website
- Add validation for QR codes that don't match expected URL patterns
- Include error handling for malformed QR codes
- Consider adding timestamps for cache invalidation in production

---

**File Generated:** January 2025  
**Last Updated:** When plant catalog changes  
**Total Plants:** 5 (Tomato, Bell Pepper, Okra, Cucumber, Zucchini)