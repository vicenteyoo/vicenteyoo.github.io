---
title:  "[Sep.2022] Ph.D. Dissertation"
excerpt: "MTPA Tracking Control of Sensorless IPMSM Based on Pulsating Voltage Signal Injection."

categories:
  - research
tags:
  - Dissertation
  - 1st Author
  - Year2022
  - Awards
last_modified_at: 2022-11-09T11:03+09:00
---

유지원, "맥동 전압 주입을 이용한 위치 센서 없는 매입형 영구자석 동기전동기의 MTPA 추종제어," 박사학위논문, 서울대학교, 2022.
J. Yoo, "MTPA Tracking Control of Sensorless IPMSM Based on Pulsating Voltage Signal Injection," Ph.D. Dissertation, 2022.
(This dissertation won the distinguished dissertation award in Seoul National University.)
[Link](https://dcollection.snu.ac.kr/public_resource/pdf/000000172330_20221109212704.pdf)  


>As the torque density of the interior permanent-magnet synchronous
motors(IPMSMs) gets higher, the more magnetically saturated IPMSM is being
developed. Below the base speed, maximum torque per Ampere(MTPA) operation
is required for the high efficiency and the maximum torque capability of IPMSM.
Therefore, an online MTPA tracking operation considering the magnetic saturation
is required.  
>
>This dissertation presents an online MTPA tracking algorithm based on the flux
model of IPMSM, which can be applied to the sensorless condition. The proposed
algorithm consists of two sub-algorithms; one is for the mid-and high-speed region
where the stator flux can be observed from the stator voltage, and the other is for the
low-speed region.  
>
>Prior to the algorithm for the mid-and high-speeds, an MTPA criterion is
formulated at an arbitrary reference frame. Furthermore, the estimated MTPA
reference frame(EMRF) is proposed, and the MTPA criterion on that frame is derived.
On the EMRF, the MTPA condition can be assessed without the rotor position
information. Moreover, the proposed MTPA criterion at the EMRF requires only one
inductance information, while the conventional criterion at the rotor reference frame
is formulated with four inductance information.  
>
>Based on the simplified MTPA criterion, an MTPA tracking algorithm for mid-and
high-speeds is proposed. The proposed method comprises a flux estimator based on
the stator voltage observation, a dynamic inductance estimator based on the pulsating
voltage injection, and an MTPA point tracking controller. This dissertation adopts
the frequency-adaptive flux observer(FAO) to estimate the stator flux information.
The discretization error of the conventional implementation of FAO is analyzed.
Based on the analysis, an FAO’s implementation at the synchronous reference frame,
robust to the discretization error, is proposed. The dynamic inductance estimator
calculates the d-axis inductance at the EMRF based on the pulsating voltage signal
injection. To enhance the estimation accuracy, the injection voltage vector is
dynamically changed by an injection voltage controller. The proposed mid- and highspeed algorithm does not need the preset inductance/flux look-up table and is
applicable to the sensorless IPMSMs.  
>
>This dissertation proposes an MTPA tracking algorithm for the low-speeds based
on the tilted pulsating voltage signal injection. Instead of the real-time flux estimator,
the proposed low-speed algorithm utilizes the inductance and flux information
obtained in the mid-and high-speed operation, which determines the direction of the
injected voltage vector. This dissertation presents a sufficient condition of IPMSM
for the stable operation of the proposed low-speed algorithm.
The proposed MTPA tracking algorithm can accurately calculate the MTPA
operating point even under the parameter variation induced by the magnetic
saturation. The performance of the proposed MTPA tracking algorithm is verified
with a 150 kW-rated IPMSM for EV application.
