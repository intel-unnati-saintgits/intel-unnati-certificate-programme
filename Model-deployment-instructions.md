# Welcome to model deployment with `Streamlit` community cloud.

# Streamlit

[Streamlit](https://streamlit.io/) is an open-source Python library that facilitates the creation of web applications for data science and machine learning projects with minimal effort. It simplifies the process of turning data scripts into shareable web apps, enabling developers to build interactive and customizable dashboards, visualizations, and applications without requiring extensive web development experience.

## Advantages for Machine Learning Developers:

1. **Rapid Prototyping:** Streamlit allows for quick and easy prototyping of machine learning models and applications. Developers can iterate and experiment faster, making it an ideal tool for the development phase.

2. **User-Friendly:** Streamlit is designed to be user-friendly, with a simple syntax that enables developers to create interactive apps using just a few lines of code. This is beneficial for machine learning practitioners who may not have extensive front-end development skills.

3. **Interactive Widgets:** The library provides a variety of interactive widgets such as sliders, buttons, and text inputs, making it easy to build interfaces for exploring and adjusting machine learning models in real-time.

4. **Integration with Data Science Libraries:** Streamlit seamlessly integrates with popular data science libraries like Pandas, NumPy, and Matplotlib, allowing developers to incorporate data analysis and visualization into their applications effortlessly.

5. **Sharing and Deployment:** Streamlit apps can be easily deployed on various platforms, including cloud services. This makes it convenient for machine learning developers to share their work with stakeholders, clients, or the wider community.

6. **Community Support:** While there may not be a specific "Streamlit Community Cloud," Streamlit benefits from an active and supportive community. Developers can find helpful resources, documentation, and examples, making it easier to troubleshoot issues and learn new features.

It's worth checking the latest [documentation](https://docs.streamlit.io/) or community updates for any new developments or features, as the field of technology can evolve rapidly.


## Instruction to use this Repo to create a ML app and deploy in `stremlit` community cloud.

> [!IMPORTANT]
>  $\text{Step 1}:-$
>Clone the required GitHub repo containing the model.py , app.py, saved model and the text file (requirements.txt) contains required libraries to run the python code.
> To do it `intel oneAPI`, follow these stpes.
> From a `Jupyterhub` terminal instance:
>- `mkdir MDeploy`
>- `cd MDeploy`
>- `git clone https://github.com/intel-unnati-saintgits/Model-Deployment-Demo`
>- `cd Model-Deployment-Demo`
>- `bash lab_setup.sh` ($\color{red} \text{Dont do this in oneAPI}$)
>- `pip install -r requirements.txt`
>- 
>$\text{Step 2}:-$
> Run all the `.py` files in the `oneAPI` to understand how to run `Python` files in the terminal.

>[!WARNING]
> It is noted that the `app.py` will execute with `python -m streamlit run app.py` in the terminal. But the output will not be shown in the said urls!
>Don't worry! You can still deploy your app in the `streamlit` cloud.

>$\text{Step 3}:-$
>
>- Create a new repository- `Deployment-Repo` in your github account.
>
>- Upload the following files one by one:
>
>`model.py` , `app.py`, `rf_model.sav' and `requirements.txt`.


>$\text{Step 4:}$
> - Create an account in the `streamlit cloud` by clicking the link: <https://streamlit.io/>
>- To deploy your app follow the instructions given in <https://docs.streamlit.io/streamlit-community-cloud/deploy-your-app>

