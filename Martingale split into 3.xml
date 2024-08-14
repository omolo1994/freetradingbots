<xml xmlns="http://www.w3.org/1999/xhtml" collection="false">
  <variables>
    <variable type="" id="p5J;VRxP~[e0LD7aQ|z}">stake</variable>
    <variable type="" id="d3oq*t4C9[8#664r~n07">initialStake</variable>
    <variable type="" id="zC)#0Vw(f|6bWYKu,7!u">MaxLoss</variable>
    <variable type="" id=":YR47L%_cD;96AmsPP5W">totalProfit</variable>
    <variable type="" id="rVEi@HLQr~5p%J;kETs1">Ticks</variable>
    <variable type="" id="G,sE`d?g5m6c}!W@N,N(">startTime</variable> 
    <variable type="" id="8W_qT7v+J#j#Vyom^I#">endTime</variable>
    <variable type="" id="*N{V`3#rE*r;j+j$Q09m">timeDifference</variable>
    <variable type="" id="Q[m=a{2n;3#_s*|A`?|R">predictedDigit</variable> 
    <variable type="" id="k3y$j2-/kG@|cV5=m;4%">consecutiveLosses</variable>
    <variable type="" id="4?%s/3?N#4j.958/p0]g">maxConsecutiveLosses</variable>
  </variables>
  
  <block type="trade" id="xgH69|xFn9=70w.*3Vo@" x="0" y="0">
    <field name="MARKET_LIST">synthetic_index</field>
    <field name="SUBMARKET_LIST">random_index</field>
    <field name="SYMBOL_LIST">1HZ50V</field> 
    <field name="TRADETYPECAT_LIST">digits</field>
    <field name="TRADETYPE_LIST">matchesdiffers</field>
    <field name="TYPE_LIST">DIGITMATCH</field> 
    <field name="CANDLEINTERVAL_LIST">60</field> 
    <field name="TIME_MACHINE_ENABLED">FALSE</field>
    <field name="RESTARTONERROR">TRUE</field>

    <statement name="INITIALIZATION">
      <block type="variables_set" id="vq}3~Rmg/)hn294Ct=#P">
        <field name="VAR" id="p5J;VRxP~[e0LD7aQ|z}">stake</field>
        <value name="VALUE">
          <block type="text_prompt_ext" id="{}G%:9.Lcx!K^R_*KO-J" collapsed="true">
            <mutation type="NUMBER"></mutation>
            <field name="TYPE">NUMBER</field>
            <value name="TEXT">
              <shadow type="text" id="O_M?FGK#I==ZG`Bwde6~">
                <field name="TEXT">Initial Stake Amount (USD)</field>
              </shadow>
            </value>
          </block>
        </value>
        <next>
          <block type="variables_set" id="d3oq*t4C9[8#664r~n07">
            <field name="VAR" id="d3oq*t4C9[8#664r~n07" variabletype="">initialStake</field> 
            <value name="VALUE">
              <block type="variables_get" id="I,G?p9!7.e=a5w~B99oN">
                <field name="VAR" id="p5J;VRxP~[e0LD7aQ|z}" variabletype="">stake</field>
              </block>
            </value>
            <next> 
              <block type="variables_set" id="y{9BI9}Z3%R}));Nt|^/">
                <field name="VAR" id="zC)#0Vw(f|6bWYKu,7!u" variabletype="">MaxLoss</field> 
                <value name="VALUE">
                  <block type="math_number" id="{~H2tKfwJ0()W~ty4N.c">
                    <field name="NUM">10</field> 
                  </block>
                </value>
                <next>
                  <block type="variables_set" id="x5183_v{g[~h6v9M86)C">
                    <field name="VAR" id=":YR47L%_cD;96AmsPP5W" variabletype="">totalProfit</field>
                    <value name="VALUE">
                      <block type="math_number" id="17}i3?j]J`dQ|f!b]B95">
                        <field name="NUM">0</field>
                      </block>
                    </value>
                    <next>
                      <block type="variables_set" id="8h`_qT7v+J#j#Vyom^I#">
                        <field name="VAR" id="rVEi@HLQr~5p%J;kETs1" variabletype="">Ticks</field>
                        <value name="VALUE">
                          <block type="math_number" id="emE/,L.E2EW%`lQMh]4[">
                            <field name="NUM">1</field>
                          </block>
                        </value>
                        <next>
                          <block type="variables_set" id="^qiS.Z/=/iE@A|g(uK|9">
                            <field name="VAR" id="k3y$j2-/kG@|cV5=m;4%">consecutiveLosses</field>
                            <value name="VALUE">
                              <block type="math_number" id="!o6i`B85@]D/M9T$o=yI">
                                <field name="NUM">0</field>
                              </block>
                            </value>
                            <next>
                              <block type="variables_set" id="b,5cI#Q-f]9=s$j/m]3c">
                                <field name="VAR" id="4?%s/3?N#4j.958/p0]g">maxConsecutiveLosses</field>
                                <value name="VALUE">
                                  <block type="math_number" id="47_x}tV*#|i+W}k?9a7{">
                                    <field name="NUM">3</field> 
                                  </block>
                                </value>
                              </block>
                            </next>
                          </block>
                        </next>
                      </block>
                    </next> 
                  </block>
                </next>
              </block>
            </next>
          </block>
        </next>
      </block>
    </statement>

    <statement name="SUBMARKET">
      <block type="tradeOptions" id="x=V33~4Lb|(sLv`J[:Eb">
        <field name="DURATIONTYPE_LIST">t</field>
        <field name="CURRENCY_LIST">USD</field>
        <value name="DURATION">
          <shadow type="math_number" id="O*@58sDc=!cOO}*b2vf9">
            <field name="NUM">5</field> 
          </shadow>
          <block type="variables_get" id="?S97)%e.5bV/b4]oF|gR">
            <field name="VAR" id="*N{V`3#rE*r;j+j$Q09m" variabletype="">timeDifference</variable>
          </block>
        </value> 
        <value name="AMOUNT">
          <shadow type="math_number" id="ml)25~7^q}3I9}vjf:%K">
            <field name="NUM">1</field>
          </shadow>
          <block type="variables_get" id="7N2omkh}3)m8/!Y}GC@%">
            <field name="VAR">stake</field>
          </block>
        </value>
        <value name="PREDICTION">
          <block type="variables_get" id="v2!ti(0ZX(b021-o3$!n
