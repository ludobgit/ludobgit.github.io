<?php

$xmlstring = <<<XML

<hesLexicon lexiconType="hs" transmittedCode="lx" version="D36" description="">

  <objects lexiconType="lt" transmittedCode="ot" version="" description="">

    <generalObjects lexiconType="ot" transmittedCode="go" version="" description="">
      <moduleType lexiconType="zz" transmittedCode="mt" version="" description="">tba</moduleType>
    </generalObjects>

    <applicationObjects lexiconType="ot" transmittedCode="ao" version="" description="" trust="" level="" >

      <utility lexiconType="ad" transmittedCode="ut" version="" description="">

        <powerSensor lexiconType="fo" transmittedCode="ps" version="" description="">
          <analogSensor lexiconType="ao" transmittedCode="as" version="" description="">
           <currentValue lexiconType="pr" transmittedCode="cv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">de</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">0</positions>                
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">wt</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">ma</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">ep</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">ou</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pr" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </currentValue>

            <previousValue lexiconType="pr" transmittedCode="pv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">de</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">0</positions>                
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">wt</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">op</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">ep</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">ou</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pr" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </previousValue>  
          </analogSensor>
        </powerSensor>

        <voltageSensor lexiconType="fo" transmittedCode="vs" version="" description="">
          <analogSensor lexiconType="ao" transmittedCode="as" version="" description="">
           <currentValue lexiconType="pr" transmittedCode="cv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">de</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">0</positions>                
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">vt</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">ma</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">ep</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">ou</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pr" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </currentValue>

            <previousValue lexiconType="pr" transmittedCode="pv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">de</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">0</positions>                
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">vt</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">op</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">ep</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">ou</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pr" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </previousValue>  
          </analogSensor>
        </voltageSensor>

        <voltageGeneration lexiconType="fo" transmittedCode="vg" version="" description="">
          <analogAcutator lexiconType="ao" transmittedCode="aa" version="" description="">
           <currentValue lexiconType="pr" transmittedCode="cv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">de</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">0</positions>                  
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">vt</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">ma</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">ep</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pr" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </currentValue>

            <previousValue lexiconType="pr" transmittedCode="pv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">de</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">0</positions>                  
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">vt</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">op</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">ep</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pb" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </previousValue>  
          </analogAcutator>
        </voltageGeneration>

        <gasSensor lexiconType="fo" transmittedCode="gs" version="" description="">
        
        </gasSensor>

      </utility>

      <lighting lexiconType="ad" transmittedCode="li" version="" description="">

        <lightLamp lexiconType="fo" transmittedCode="ll" version="" description="">
          <digitalActuator lexiconType="ao" transmittedCode="da" version="" description="">
           <currentValue lexiconType="pr" transmittedCode="cv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">zo</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">2</positions>      
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">no</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">ma</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">li</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pb" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </currentValue>

            <previousValue lexiconType="pr" transmittedCode="pv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">zo</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">2</positions>                 
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">no</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">op</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">li</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pb" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </previousValue>  
          </digitalActuator>

          <digitalSensor lexiconType="ao" transmittedCode="ds" version="" description="">
           <currentValue lexiconType="pr" transmittedCode="cv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">zo</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">2</positions>      
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">no</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">ma</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">li</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">ou</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pr" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </currentValue>

            <previousValue lexiconType="pr" transmittedCode="pv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">zo</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">2</positions>                 
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">no</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">op</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">li</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">ou</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pr" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </previousValue>  
          </digitalSensor>          
        </lightLamp>

      </lighting>  

      <hvac lexiconType="ad" transmittedCode="hv" version="" description="">

        <tempSensor lexiconType="fo" transmittedCode="ts" version="" description="">
          <analogSensor lexiconType="ao" transmittedCode="as" version="" description="">
           <currentValue lexiconType="pr" transmittedCode="cv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">de</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">0</positions>                
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr"></unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">ma</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">tp</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">ou</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pr" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </currentValue>

            <previousValue lexiconType="pr" transmittedCode="pv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">de</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">0</positions>                
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr"></unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">op</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">tp</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">ou</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pr" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </previousValue>  
          </analogSensor>       
        </tempSensor>
 
        <humiditySensor lexiconType="fo" transmittedCode="hs" version="" description="">
          <analogSensor lexiconType="ao" transmittedCode="as" version="" description="">
           <currentValue lexiconType="pr" transmittedCode="cv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">de</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">0</positions>                
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">ph</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">ma</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">hu</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">ou</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pr" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </currentValue>

            <previousValue lexiconType="pr" transmittedCode="pv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">de</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">0</positions>                
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">ph</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">op</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">hu</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">ou</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pr" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </previousValue>  
          </analogSensor>       
        </humiditySensor> 

        <heatingRoomController lexiconType="fo" transmittedCode="hc" version="" description="">
          <analogAcutator lexiconType="ao" transmittedCode="aa" version="" description="">
            <currentValue lexiconType="pr" transmittedCode="cv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">de</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">0</positions>                  
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr"></unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">co</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">tp</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pb" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </currentValue>

            <previousValue lexiconType="pr" transmittedCode="pv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">de</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">0</positions>                  
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr"></unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">co</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">tp</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pb" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </previousValue>  
          </analogAcutator>
        </heatingRoomController>

        <coolingRoomController lexiconType="fo" transmittedCode="cc" version="" description="">
          <analogAcutator lexiconType="ao" transmittedCode="aa" version="" description="">
            <currentValue lexiconType="pr" transmittedCode="cv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">de</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">0</positions>                  
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr"></unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">co</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">tp</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pb" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </currentValue>

            <previousValue lexiconType="pr" transmittedCode="pv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">de</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">0</positions>                  
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr"></unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">co</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">tp</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pb" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </previousValue>  
          </analogAcutator>
        </coolingRoomController>

        <autoRoomController lexiconType="fo" transmittedCode="ac" version="" description="">
          <analogAcutator lexiconType="ao" transmittedCode="aa" version="" description="">
            <currentValue lexiconType="pr" transmittedCode="cv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">de</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">0</positions>                  
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr"></unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">co</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">tp</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pb" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </currentValue>

            <previousValue lexiconType="pr" transmittedCode="pv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">de</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">0</positions>                  
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr"></unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">co</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">tp</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pb" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </previousValue>  
          </analogAcutator>
        </autoRoomController>

        <hvacModeController lexiconType="fo" transmittedCode="mc" version="" description="">
          <digitalActuator lexiconType="ao" transmittedCode="da" version="" description="">
           <currentValue lexiconType="pr" transmittedCode="cv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">nn</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr"></positions>      
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">no</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">ma</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">tp</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pb" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </currentValue>

            <previousValue lexiconType="pr" transmittedCode="pv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">nn</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr"></positions>                 
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">no</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">op</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">tp</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pb" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </previousValue>  
          </digitalActuator>
        </hvacModeController>

        <fanController lexiconType="fo" transmittedCode="fc" version="" description="">
          <digitalActuator lexiconType="ao" transmittedCode="da" version="" description="">
           <currentValue lexiconType="pr" transmittedCode="cv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">nn</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr"></positions>      
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">no</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">ma</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">vt</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pb" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </currentValue>

            <previousValue lexiconType="pr" transmittedCode="pv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">nn</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr"></positions>                 
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">no</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">op</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">vt</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pb" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </previousValue>  
          </digitalActuator>
        </fanController>
      </hvac>

      <convenience lexiconType="ad" transmittedCode="cn" version="" description="">
        <applianceController lexiconType="fo" transmittedCode="ac" version="" description="">
          <digitalActuator lexiconType="ao" transmittedCode="da" version="" description="">
           <currentValue lexiconType="pr" transmittedCode="cv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">zo</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">2</positions>      
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">no</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">ma</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr"></propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pb" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </currentValue>

            <previousValue lexiconType="pr" transmittedCode="pv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">zo</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">2</positions>                 
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">no</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">op</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr"></propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pb" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </previousValue>  
          </digitalActuator>        
        </applianceController>

        <applianceSensor lexiconType="fo" transmittedCode="as" version="" description="">
          <digitalSensor lexiconType="ao" transmittedCode="ds" version="" description="">
           <currentValue lexiconType="pr" transmittedCode="cv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">zo</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">2</positions>      
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">no</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">ma</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr"></propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">ou</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pr" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </currentValue>

            <previousValue lexiconType="pr" transmittedCode="pv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">zo</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">2</positions>                 
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">no</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">op</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr"></propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">ou</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pr" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </previousValue>  
          </digitalSensor> 
        </applianceSensor>  
      </convenience>

      <userInterface lexiconType="ad" transmittedCode="ui" version="" description="">  

        <uiStatus lexiconType="fo" transmittedCode="us" version="" description="">
          <digitalSensor lexiconType="ao" transmittedCode="ds" version="" description="">
           <currentValue lexiconType="pr" transmittedCode="cv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr"></dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr"></numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr"></positions>      
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">no</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">ma</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">no</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">ou</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pr" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </currentValue>

            <previousValue lexiconType="pr" transmittedCode="pv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr"></dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr"></numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr"></positions>                 
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">no</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">op</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">no</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">ou</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pr" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </previousValue>  
          </digitalSensor> 
        </uiStatus>

        <uiDisplay lexiconType="fo" transmittedCode="ud" version="" description="">
          <digitalActuator lexiconType="ao" transmittedCode="da" version="" description="">
           <currentValue lexiconType="pr" transmittedCode="cv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr"></dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr"></numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr"></positions>      
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">no</unitsOfMeasure>              
              <persistence lexiconType="pc" transmittedCode="pe"  version="" description="" readWrite="cr"></persistence>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">ma</support>              
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr">no</propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pb" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </currentValue>

            <previousValue lexiconType="pr" transmittedCode="pv" version="" description="">
              <dataType lexiconType="pc" transmittedCode="dt"  version="" description="" readWrite="cr">zo</dataType>
              <numElements lexiconType="pc" transmittedCode="ne"  version="" description="" readWrite="cr">1</numElements>
              <positions lexiconType="pc" transmittedCode="po"  version="" description="" readWrite="cr">2</positions>                 
              <unitsOfMeasure lexiconType="pc" transmittedCode="um"  version="" description="" readWrite="cr">no</unitsOfMeasure>              
              <support lexiconType="pc" transmittedCode="sp"  version="" description="" readWrite="cr">op</support>  
              <persistence lexiconType="pc" transmittedCode="pe"  version="" description="" readWrite="cr"></persistence>                            
              <propertyType lexiconType="pc" transmittedCode="pt"  version="" description="" readWrite="cr"></propertyType>
              <access lexiconType="pc" transmittedCode="ac"  version="" description="" readWrite="cr">in</access>
              <value lexiconType="pc" transmittedCode="va" version="" description="Value of property" readWrite="pb" ></value>
              <default lexiconType="pc" transmittedCode="df"  version="" description="" readWrite="dr"></default>
              <minimum lexiconType="pc" transmittedCode="mn"  version="" description="" readWrite="dr"></minimum>
              <maximum lexiconType="pc" transmittedCode="mx"  version="" description="" readWrite="dr"></maximum>
            </previousValue>  
          </digitalActuator>        
        </uiDisplay>

      </userInterface>

      <audioVideo lexiconType="ad" transmittedCode="av" version="" description="">
      </audioVideo>

      <communications lexiconType="ad" transmittedCode="cm" version="" description="">
      </communications>

      <security lexiconType="ad" transmittedCode="sc" version="" description="">     
      </security>

      <appliance lexiconType="ad" transmittedCode="ap" version="" description="">    
      </appliance>

      <general lexiconType="ad" transmittedCode="ge" version="" description="">
      </general>


    </applicationObjects>

    <serviceObjects lexiconType="ot" transmittedCode="so" version="" description="">

      <bindingMap lexiconType="sd" transmittedCode="bm" version="" description="">
        <mandatory lexiconType="zz" transmittedCode="ma" version="" description="" readWrite="cb">ye</mandatory>
        <single lexiconType="zz" transmittedCode="si" version="" description="" readWrite="cb">ye</single> 

        <operationTable lexiconType="zz" transmittedCode="ot" version="" description="" table="ye"> 
            <operRow lexiconType="zz" transmittedCode="or" version="" description="" index="" tableRow="ye" table="ye">
              <inputs lexiconType="zz" transmittedCode="in" version="" description="" table="ye">
                <sourceAddress lexiconType="zz" transmittedCode="sa" version="" description="" readWrite="cb" index="" tableRow="ye"></sourceAddress>
                <sourceObject lexiconType="zz" transmittedCode="so" version="" description="" readWrite="cb" index="" tableRow="ye"></sourceObject>
                <sourceValue lexiconType="zz" transmittedCode="sv" version="" description="" readWrite="pb" index="" tableRow="ye"></sourceValue>                
                <sourceTranslator lexiconType="zz" transmittedCode="st" version="" description="" readWrite="cb" index="" tableRow="ye"></sourceTranslator>
               </inputs>            
              <operation lexiconType="zz" transmittedCode="op" version="" description="" readWrite="cb"></operation>
               <inputParameters lexiconType="zz" transmittedCode="is" version="" description="" table="ye">
                 <inputParameter lexiconType="zz" transmittedCode="ip" version="" description="" readWrite="cb" index="" tableRow="ye"></inputParameter>
              </inputParameters>   
             <outputParameters lexiconType="zz" transmittedCode="os" version="" description="" table="ye">
                <outputParameter lexiconType="zz" transmittedCode="op" version="" description="" readWrite="cb" index="" tableRow="ye"></outputParameter>
              </outputParameters>
              <destTranslator lexiconType="zz" transmittedCode="to" version="" description="" readWrite="cb"></destTranslator>
              <destAddress lexiconType="zz" transmittedCode="da" version="" description="" readWrite="cb"></destAddress>
              <destObject lexiconType="zz" transmittedCode="do" version="" description="" readWrite="cb"></destObject>
              <destValue lexiconType="zz" transmittedCode="dv" version="" description="" readWrite="pb"></destValue>                   
              <authorizationType lexiconType="zz" transmittedCode="at" version="" description="" readWrite="cb"></authorizationType>
              <optInOut lexiconType="zz" transmittedCode="op" version="" description="" readWrite="cb"></optInOut>              
            </operRow>  
        </operationTable>
        <encryptionKeyTable lexiconType="zz" transmittedCode="ek" version="" description="" table="ye">
          <encrRow lexiconType="zz" transmittedCode="er" version="" description="" index="" tableRow="ye">
            <moduleType lexiconType="zz" transmittedCode="mt" version="" description="" readWrite="cb"></moduleType>
            <modRefId lexiconType="zz" transmittedCode="mi" version="" description="" readWrite="cb"></modRefId>
            <encryptionKey lexiconType="zz" transmittedCode="ek" version="" description="" readWrite="cb"></encryptionKey>
            <encryptionType lexiconType="zz" transmittedCode="et" version="" description="" readWrite="cb"></encryptionType>  
            <encryptionSubType lexiconType="zz" transmittedCode="es" version="" description="" readWrite="cb"></encryptionSubType>  
            <encryptionLength lexiconType="zz" transmittedCode="el" version="" description="" readWrite="cb"></encryptionLength>           
          </encrRow>
        </encryptionKeyTable>          
      </bindingMap>

      <identification lexiconType="sd" transmittedCode="id" version="" description="">
        <mandatory lexiconType="zz" transmittedCode="ma" version="" description="" readWrite="cb">ye</mandatory>
        <single lexiconType="zz" transmittedCode="si" version="" description="" readWrite="cb">ye</single>

        <properties lexiconType="zz" transmittedCode="pr" version="" description="">

          <uniquePublicID lexiconType="zz" transmittedCode="pi" version="" description="">
            <mandatory lexiconType="zz" transmittedCode="ma" version="" description="" readWrite="cb">ye</mandatory>
            <dataType lexiconType="zz" transmittedCode="dt" version="" description="" readWrite="cb">ro</dataType>
          </uniquePublicID>

          <systemNumber lexiconType="zz" transmittedCode="sn" version="" description="">
             <mandatory lexiconType="zz" transmittedCode="ma" version="" description="" readWrite="cb">ye</mandatory>
             <dataType lexiconType="zz" transmittedCode="dt" version="" description="" readWrite="cb">db</dataType>
          </systemNumber>  

          <digitalFingerPrint lexiconType="zz" transmittedCode="fp" version="" description="">
            <mandatory lexiconType="zz" transmittedCode="ma" version="" description="" readWrite="cb">ye</mandatory>
            <dataType lexiconType="zz" transmittedCode="dt" version="" description="" readWrite="cb">sp</dataType>
          </digitalFingerPrint>  

          <publicdescription lexiconType="zz" transmittedCode="pd" version="" description="">
            <mandatory lexiconType="zz" transmittedCode="ma" version="" description="" readWrite="cb">no</mandatory>
            <dataType lexiconType="zz" transmittedCode="dt" version="" description="" readWrite="cb">db</dataType>
          </publicdescription>   

        </properties>
      </identification>   

      <commonUserInterface lexiconType="sd" transmittedCode="cu" version="" description="">
        <mandatory lexiconType="zz" transmittedCode="ma" version="" description="" readWrite="cb">no</mandatory>
        <single lexiconType="zz" transmittedCode="si" version="" description="" readWrite="cb">ye</single>                 
      </commonUserInterface> 

      <clusterToCluster lexiconType="sd" transmittedCode="cc" version="" description="">
        <mandatory lexiconType="zz" transmittedCode="ma" version="" description="" readWrite="cb">no</mandatory>
        <single lexiconType="zz" transmittedCode="si" version="" description="" readWrite="cb">ye</single>                 
      </clusterToCluster> 

      <encryption lexiconType="sd" transmittedCode="en" version="" description="">
        <mandatory lexiconType="zz" transmittedCode="ma" version="" description="" readWrite="cb">no</mandatory>
        <single lexiconType="zz" transmittedCode="si" version="" description="" readWrite="cb">no</single>               
      </encryption>

      <authorization lexiconType="sd" transmittedCode="au" version="" description="Authorization and consent">
        <mandatory lexiconType="zz" transmittedCode="ma" version="" description="" readWrite="cb">ye</mandatory>
        <single lexiconType="zz" transmittedCode="si" version="" description="" readWrite="cb">ye</single> 
      </authorization>     

      <time lexiconType="sd" transmittedCode="tm" version="" description="">
        <mandatory lexiconType="zz" transmittedCode="ma" version="" description="" readWrite="cb">ye</mandatory>
        <single lexiconType="zz" transmittedCode="si" version="" description="" readWrite="cb">ye</single>                 
      </time> 

      <artificialIntelligence lexiconType="sd" transmittedCode="ge" version="" description="">
        <mandatory lexiconType="zz" transmittedCode="ma" version="" description="" readWrite="cb"></mandatory>
        <single lexiconType="zz" transmittedCode="si" version="" description="" readWrite="cb"></single>                
      </artificialIntelligence>        

      <general lexiconType="sd" transmittedCode="ge" version="" description="">
        <mandatory lexiconType="zz" transmittedCode="ma" version="" description="" readWrite="cb"></mandatory>
        <single lexiconType="zz" transmittedCode="si" version="" description="" readWrite="cb"></single>                
      </general>        
    </serviceObjects>

    <interfaceObjects lexiconType="ot" transmittedCode="io" version="" description="">

      <generalInterfaceObjects lexiconType="it" transmittedCode="go" version="" description="">
      </generalInterfaceObjects>

      <hanInterfaceObjects lexiconType="it" transmittedCode="ho" version="" description="">
        <hanCharacteristics lexiconType="ct" transmittedCode="hc" version="" description="">
          <hesClipversion lexiconType="ch" transmittedCode="cv" version="" description=""></hesClipversion>
          <hanType lexiconType="ch" transmittedCode="ht" version="" description=""></hanType>    
          <version lexiconType="ch" transmittedCode="vr" version="" description=""></version>                                     
          <direction lexiconType="ch" transmittedCode="di" version="" description=""></direction>   
          <wanLinks lexiconType="ch" transmittedCode="wl" version="" description=""></wanLinks>                       
          <encrypt lexiconType="ch" transmittedCode="en" version="" description=""></encrypt>   
          <freq lexiconType="ch" transmittedCode="fr" version="" description=""></freq>   
          <media lexiconType="ch" transmittedCode="me" version="" description=""></media>                               
        </hanCharacteristics> 
      </hanInterfaceObjects>

      <wanInterfaceObjects lexiconType="it" transmittedCode="wo" version="" description="">
        <wanCharacteristics lexiconType="ct" transmittedCode="wc" version="" description="">
          <hesClipversion lexiconType="ch" transmittedCode="cv" version="" description=""></hesClipversion>
          <wanType lexiconType="ch" transmittedCode="wt" version="" description=""></wanType>                              
          <maxSpeed lexiconType="ch" transmittedCode="ms" version="" description=""></maxSpeed>    
          <media lexiconType="ch" transmittedCode="me" version="" description=""></media>                                           
        </wanCharacteristics>                
      </wanInterfaceObjects>                    

    </interfaceObjects>
  </objects>

  <actions lexiconType="lt" transmittedCode="ac" version="" description="">
    <primitive lexiconType="zz" transmittedCode="pr" version="" description="">
      <get></get>
      <set></set>
    </primitive>
    <functional lexiconType="zz" transmittedCode="fu" version="" description="">
      <getIndexLinked></getIndexLinked>
      <setIndexLinked></setIndexLinked>
    </functional>
  </actions>

</hesLexicon>

XML;

header("Content-type: text/xml");

print($xmlstring);

?>


