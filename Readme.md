Connect Photon/Electron to a CurrentCost unit via the RJ45 interface underneat and replace the NetSmart


Pin outs:

1 Vcc supply
4 GND
7 EnviR Unit Rx Data
8 EnviR Unit Tx Data


Data:

<msg>          
   <src>CC128-v0.11</src> 
   <dsb>00089</dsb>     
   <time>13:02:39</time>     
   <tmpr>18.7</tmpr>        
   <sensor>1</sensor>     
   <id>01234</id>                
   <type>1</type>              
   <ch1>
      <watts>00345</watts>
   </ch1>
   <ch2>
      <watts>02151</watts>
   </ch2>
   <ch3>
      <watts>00000</watts>
   </ch3>
</msg>


Expected Serial interface:

 baudrate: 57600,
  dataBits: 8,
  parity: 'none',
  stopBits: 1