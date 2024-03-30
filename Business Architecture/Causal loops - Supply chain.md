[[Business Architecture]] | [[Stock and flow Supply chain]]
#### System Boundary:
The system boundary will encompass the end-to-end supply chain processes of Farm Corp, from supplier engagement to product delivery to the end customer. This includes supplier selection and management, production processes, inventory management, order fulfillment, distribution logistics, and customer service. External factors such as market demand, competition, and economic conditions will also be considered as they influence the supply chain dynamics.

#### Time Horizon:
The time horizon for the model will be set to a medium-term range, typically one to three years. This allows for capturing the effects of strategic decisions, market trends, and the cyclical nature of agricultural demand. It also provides a reasonable timeframe to assess the impact of changes in supply chain policies and technological implementations.

![[Pasted image 20240322105228.png]]

> How to read:
> **Inventory tracking -> Warehouse Management (WM):** Positive Effect: Real-time inventory tracking provides accurate data for warehouse management, improving stock placement, retrieval efficiency, and overall warehouse operations.
> ![[Pasted image 20240322105702.png]]
### Balancing feedback loops

![[causalloop.png]]

Balancing feedback loops in a causal loop diagram help to stabilize the system by counteracting changes and bringing the system back to equilibrium. In the context of Farm Corp's supply chain,  balancing feedback loops between groups of causal loop variables include:

1. **Inventory Management and Supplier Performance**
    
    - **Loop**: Real-time Inventory Tracking (RIT) -> Inventory Levels (IL) -> Order Fulfillment Rate (OFR) -> Customer Satisfaction (CS) -> Market Demand (MD) -> Demand Forecasting and Replenishment (DFR) -> Supplier Performance Management (SPM) -> Supplier Availability (SA) -> Ordering Materials (OM) -> Inventory Levels (IL)
    - **Balancing Effect**: As inventory levels adjust to meet market demand, supplier performance management ensures suppliers meet the required standards. If supplier availability is impacted negatively, the system compensates by adjusting material ordering, which in turn balances inventory levels.
2. **Demand Forecasting and Market Conditions**
    
    - **Loop**: Market Demand (MD) -> Demand Forecast Accuracy (DFA) -> Demand Forecasting and Replenishment (DFR) -> Inventory Levels (IL) -> Warehouse Management (WM) -> Order Fulfillment Rate (OFR) -> Customer Satisfaction (CS) -> Market Demand (MD)
    - **Balancing Effect**: Accurate demand forecasting leads to optimized inventory levels, which supports effective warehouse management and order fulfillment. As customer satisfaction impacts market demand, the feedback loop ensures that demand forecasting is continually refined to balance with actual market conditions.
3. **Production Efficiency and Quality Control**
    
    - **Loop**: Supplier Performance Management (SPM) -> Material Costs (MC) -> Product Quality (PQ) -> Customer Satisfaction (CS) -> Market Demand (MD) -> Production Rate (PR) -> Quality Assurance (QA) -> Supplier Performance Management (SPM)
    - **Balancing Effect**: As production rates increase to meet market demand, quality assurance processes ensure product quality is maintained, which feeds back into supplier performance management. If material costs rise and impact product quality, the loop triggers adjustments in supplier management to balance cost with quality.
4. **Logistics Coordination and Carrier Performance**
    
    - **Loop**: Carrier Performance Tracking (CPT) -> Dynamic Routing and Re-routing (DRR) -> Logistics & Distribution (LD) -> Order Fulfillment Rate (OFR) -> Customer Satisfaction (CS) -> Carrier Performance Tracking (CPT)
    - **Balancing Effect**: Carrier performance tracking influences dynamic routing decisions, which affect logistics and distribution efficiency. If customer satisfaction declines due to delivery issues, the feedback loop prompts a reassessment of carrier performance and routing strategies to balance and improve logistics operations.
5. **Regulatory Compliance and Customs Management**
    
    - **Loop**: Regulatory Environment (RE) -> Customs and Compliance Management (CCM) -> Planning Transportation Routes and Schedules (PTRS) -> Logistics & Distribution (LD) -> Market Demand (MD) -> Regulatory Environment (RE)
    - **Balancing Effect**: Changes in the regulatory environment affect customs and compliance management, which impacts transportation planning. As market demand responds to logistics efficiency, the regulatory environment is monitored to ensure compliance, creating a balancing loop that adjusts transportation planning accordingly.

These balancing feedback loops illustrate the self-regulating mechanisms within Farm Corp's supply chain, ensuring that the system can adapt and maintain stability in response to internal changes and external pressures.

### Reinforcing feedback loops

Reinforcing feedback loops in a causal loop diagram represent self-reinforcing processes that can lead to exponential growth or decline within a system. In Farm Corp's supply chain, the following are potential reinforcing feedback loops between groups of causal loop variables:

1. **Market Demand and Production Scaling**
    
    - **Loop**: Market Demand (MD) -> Order Fulfillment Rate (OFR) -> Customer Satisfaction (CS) -> Market Demand (MD)
    - **Reinforcing Effect**: As market demand increases, efforts to maintain a high order fulfillment rate lead to greater customer satisfaction, which in turn can further increase market demand, creating a virtuous cycle of growth.
2. **Supplier Performance and Inventory Optimization**
    
    - **Loop**: Supplier Performance Management (SPM) -> Supplier Reliability (SR) -> Real-time Inventory Tracking (RIT) -> Demand Forecasting and Replenishment (DFR) -> Supplier Performance Management (SPM)
    - **Reinforcing Effect**: Better supplier performance management improves supplier reliability, which enhances real-time inventory tracking and, consequently, demand forecasting and replenishment. This loop can lead to increasingly optimized inventory levels and further improvements in supplier performance management.
3. **Quality Assurance and Brand Reputation**
    
    - **Loop**: Product Quality (PQ) -> Customer Satisfaction (CS) -> Brand Management (BM) -> Market Demand (MD) -> Production Rate (PR) -> Quality Assurance (QA) -> Product Quality (PQ)
    - **Reinforcing Effect**: High product quality boosts customer satisfaction, enhancing brand reputation and increasing market demand. As production rates rise to meet demand, a focus on quality assurance ensures that product quality is maintained or improved, reinforcing the brand's reputation and demand.
4. **Continuous Improvement and Innovation Feedback**
    
    - **Loop**: Continuous Improvement and Innovation (CII) -> Production Efficiency (PE) -> Cost Savings (CS) -> Investment in Technology (IT) -> Continuous Improvement and Innovation (CII)
    - **Reinforcing Effect**: Continuous improvement and innovation lead to increased production efficiency, resulting in cost savings. These savings can be reinvested in technology, which further drives continuous improvement and innovation, creating a cycle of ongoing enhancement.
5. **Technology Adoption and Supply Chain Agility**
    
    - **Loop**: Technological Advancements (TA) -> Supply Chain Flexibility and Responsiveness (SCFR) -> Market Competitiveness (MC) -> Investment in Technology (IT) -> Technological Advancements (TA)
    - **Reinforcing Effect**: Adoption of new technologies enhances supply chain flexibility and responsiveness, improving market competitiveness. This success leads to more investment in technology, which drives further technological advancements and reinforces the supply chain's agility.

These reinforcing feedback loops highlight areas within the supply chain where strategic interventions can significantly amplify positive outcomes or, conversely, where negative trends may escalate if not addressed.