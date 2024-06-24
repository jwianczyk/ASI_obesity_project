# PJA-ASI-14C-GR2
# **Project for ASI, PJAIT 2024**

## **Prerequisites** 
* PC/Laptop with linux/windows/macOS operating system
* Conda=24.1.2

## **Instalation**
1. Clone repo
2. Set conda forge channels
    * `conda config --add channels conda-forge`
    * `conda config --set channel_priority strict`
3. Set and activate environment - `conda create --name {environment name}`
4. Install packages - `conda install --file packages.yml`
5. Check if packages are installed - `pip freeze`


- [x] ~~~Fork repo~~~
- [ ] Clean repo
- [ ] Attach GitHub Actions as CI/CD
- [ ] Set RDS as a default data source for pipeline
- [ ] Set CI/CD to push docker images to ECR
- [ ] Configure input appending for rds in predict endpoint
- [ ] Configure docker compose for both containers 
- [ ] Add Swagger UI compatibility for API testing
