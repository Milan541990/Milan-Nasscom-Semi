## Testing at different stages
* Testing in semiconductor manufacturing happens at multiple stages to ensure functionality and quality. It starts at the foundry with wafer probe testing after front-end manufacturing. Next, wafer sorting identifies good dies for packaging. At the OSAT stage, the chip goes through package manufacturing followed by package-level testing. Finally, System Level Testing (SLT) verifies the chip in real-world usage scenarios. Throughout all stages, diagnosis and failure analysis help improve process development and yield.
<img src="/imga.png">

## Package Testing
* Package Testing begins after the packaging process is completed in a cleanroom (ISO class 6 & 7), where steps like die bonding and encapsulation occur. After singulation, the packages are placed in trays and loaded into sockets or boards for testing. The first step is AOST (Assembly Open and Short Test), which checks for basic connectivity issues. Next is the Burn-in stage, where packages are exposed to thermal and voltage stress to screen out early failures. Following that is the Final Test, which includes cold and hot tests to ensure the device meets functional, parametric, and reliability specifications. This test confirms the performance across various operating temperatures. Throughout, inspections play an essential role in quality control. These stages ensure only fully functional and reliable chips move forward to system-level integration.
<img src="/imgb.png">

## Assembly Open and Short test(AOST) - Functionality
* AOST is a quick electrical test to detect shorts or opens on package leads or balls.
* It is performed right after Trim and Form (for leadframe packages) or Singulation (for BGA packages).
* The main goal is to catch major electrical failures before the product leaves assembly.
* AOST includes vision inspection to detect damaged, missing, or misaligned leads or solder balls.
* It also checks for common issues like Head on Pillow (HoP), bridging, and non-wet opens (NWO).
* Die cracks and package warpage are detected visually or through inspection tools.
* The Product Grade Sort (PGSRT) system categorizes the devices into Best (1), Better (2/3), and Scrap (4).
* Testing is done using automated handlers and probes to ensure accuracy and speed.
* It plays a crucial role in yield improvement and quality control.
* AOST ensures only electrically sound packages proceed to the next stages.
<img src="/imgc.png">

## Burn-in Test
* Objective: To test components under elevated stress (temperature, voltage, power cycling) to catch early failures.
* The main goal is to detect "Infant Mortality" failures before the product reaches customers.
* Devices are placed on Burn-in boards and tested inside Burn-in systems (ovens).
* The process uses high voltage and high temperature to accelerate failures.
* Testing continues until the initial failure rate flattens, ensuring weak units are filtered out.
* Common defects detected include dielectric breakdown, metallization failures, and electromigration.
* The test helps in improving overall reliability by removing faulty components.
* The burn-in test may reduce the overall lifespan slightly due to stress exposure.
* The failure curve shows a drop in early failures, followed by a stable useful life.
* Burn-in is critical for high-reliability applications like aerospace, automotive, and servers.
<img src="/imgd.png">

## Final test
* The Final Test is a temperature corner test to verify if the packaged product meets all electrical specifications. Parts are tested using ATE (Automated Test Equipment) with temperature-controlled handlers, not ovens. A Hot Test checks functionality at elevated temperatures per product specs. A Cold Test ensures the product performs correctly at low temperatures. Both tests confirm reliability and electrical behavior across operating extremes. This ensures only fully qualified chips proceed to shipment or system integration.
<img src="/imge.png">

## ATE
* Automatic Test Equipment (ATE) automates the testing of semiconductor devices by sending test patterns to the Device Under Test (DUT). It performs three major test types:
- Parametric Tests measure voltage or current to ensure circuit parameters are within spec.
- Functional Tests check the device's behavior under normal operating conditions.
- Speed Tests verify timing performance as per datasheet, and sort parts accordingly.Testing efficiency is evaluated by yield, test time, and test coverage.Handlers and robotic arms like COBOT help automate part placement and handling during tests.
<img src="/imgf.png">
