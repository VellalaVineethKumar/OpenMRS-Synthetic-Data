
Hello everyone, my name is Vineeth Vellala and I'm excited to share my research on generating synthetic medical data using normalising flows. Synthetic data plays a crucial role in healthcare research and education, especially in resource-constrained settings where access to real patient data is limited due to privacy concerns.Background and Objectives (1 minute)
![alt text](https://github.com/VellalaVineethKumar/OpenMRS-Synthetic-Data/blob/main/download%20(6).png)
Electronic health records, or EHRs, contain valuable information for research, algorithm development, and educational purposes. However, accessing this data is challenging due to strict privacy regulations. My hypothesis is that normalising flow models can learn the probability density of the MIMIC-IV dataset to generate useful synthetic data that closely matches the original. The key objectives of this research are:

1. To provide a privacy-preserving solution for medical research and education
2. To generate realistic patient data that achieves a 95% match with key health indicators from the original EHR data
3. To enable third-world countries to access high-quality synthetic data through integration with OpenMRS
4. To ensure 100% GDPR compliance in the synthetic data generation process

Materials and Methods (1 minute)

For this research, I utilized the MIMIC-IV dataset, a large, freely available database of de-identified electronic health records. I developed and compared normalising flow models using the nflows library and Generative Adversarial Networks, or GANs, for generating realistic synthetic EHR data. The architecture diagram on the poster provides an overview of the process.Results (2 minutes)

I'm pleased to report that the normalising flow model successfully generated synthetic medical data that closely resembles the original MIMIC-IV dataset for patient height and weight.The table on the poster compares the mean and standard deviation between the original and synthetic data, showing a close match.The density plots further illustrate the similar distributions between the original and synthetic data for both height and weight.Additionally, Kolmogorov-Smirnov tests indicate no significant difference between the original and synthetic data, with p-values of 0.0341 for height and 0.025 for weight.Conclusion and Future Work (30 seconds)


In conclusion, this research demonstrates the potential of normalising flows in generating high-quality synthetic medical data while preserving patient privacy. The next steps involve expanding the model to include more health indicators and further improving the quality of the synthetic data. I also plan to integrate the generated synthetic data with OpenMRS to benefit resource-constrained countries.
