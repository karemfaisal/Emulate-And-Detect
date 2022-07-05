# Emulate and Detect
> Emulate and Detect repository aims to have a comprehensive and reliable adversary emulation tests along with their detection use cases.
>
> The Adversary emulation become a very widely used approach to spot the gap in the detection capabilities, as by emulating the set of techniques used by the adversaries and monitor for the detection/prevention of the deployed security controls, the entities can define their gap, then enhance their detection capabilities either by adding detection use cases or any other Infrastructure recommendations.



Each technique in these repository will have the following if possible:

- SIGMA rule describing the detection.
  - Windows/Linux detection use cases contains multiple separate YAML sections that uses built-in windows/Linux events and Sysmon-Auditd events. 
  
    *Sysmon/Auditd Events could be mapped to the EDR-equivalent events.*
  
- Suricata rule for the network detection.
  
- Atomic Red test for emulation.



### Threat detection Quality Insurance

Quality insurance is the main factor while creating the detection use cases, The contributors follow a comprehensive and concrete life cycle to produce the detection use cases with low false-positive and false-negative rates.

This life cycle contains an emulation for the attack and monitoring for the false positive rate along with multiple quality insurance criteria.

 
