# Primary
hey folks, this is our(or just my) first relatively big project, this readme file is used to log some reminders in case we miss some
big point.

---

2018.9.15
add login interface

---

2018.9.19
new data structure
```java
private String AlloyName,NamingStandard,Component;
    private double Density,ThermalExpan,ThermalCon,SpecificHeat,Resistivity,ElasticModu,PoissonsRatio,MeltingRange_Min,MeltingRange_Max,DampingIndex,
            Hardness_Min, Hardness_Max;
    private String Forging, Weldability, Machining, SurfaceTreatment, CorrisionResistance;
    private double FractureToughness;
    public boolean[] Validation = new boolean[19];
```

validation[0]->AlloyName
validation[1]->NamingStandard
validation[2]->Component
validation[3]->Density
validation[4]->ThermalExpan
validation[5]->ThermalCon
validation[6]->SpecificHeat
validation[7]->Resistivity
validation[8]->ElasticModu
validation[9]->PoissonsRatio
validation[10]->MeltingRange
validation[11]->DampingIndex
validation[12]->Hardness
validation[13]->Forging
validation[14]->Weldability
validation[15]->Machining
validation[16]->SurfaceTreatment
validation[17]->CorrisionResistance
validation[18]->FractureToughness
