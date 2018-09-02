# -Quantitative-Finance-

 
Lecturer: Sergey V. Gelman, Leonid Timoschuck Class teachers: Eugeny R. Nadorshin, Kirill Melkumiants, Sergey Vedernikov 
 
Course description 
 
The course provides coverage of important topics in modern Quantitative Finance and Risk Management at the advanced undergraduate level. It is intended for the 4th-year undergraduate students of the International College of Economics and Finance, High School of Economics, Moscow. Particular attention is given to the topics such as the Efficient Market Hypothesis, financial markets micro-structure and types of arbitrage, general principles of modelling the price dynamics of financial assets, market risk and other types of financial risks, Value-at-Risk (VaR) approach and applications, modelling of extreme market events, VaR analysis for financial derivatives using the Kolmogorov equations framework, foundations of the copula methods, modelling of periodic and quasi-periodic trends in time series in connection with technical analysis, and the foundations of high-frequency arbitrage trading. The topics covered in this course will enable the students to develop the theoretical knowledge and practical skills required for successful working with multiple types of risks in modern financial markets, both Russian and international. The course is taught in English. 
 
The prerequisites for the course are Elements of Econometrics and Microeconomics. Good command of methods of calculus, general probability theory and mathematical statistics are also required for the course. 
 
Teaching objectives The goal of this course is to give students insights in the functioning of financial markets, understanding of measuring and forecasting financial risks. This course is aimed at giving students instruments required in order to analyze issues in asset pricing and market finance. After the course students should be familiar with recent empirical findings based on financial econometric models, have a good command of basic econometric techniques and understand practical issues in the forecasting of key financial market variables 
 
Teaching methods 
 
The following methods and forms of study are used in the course: - lectures (2 hours per week); - practical classes, also in computer class (2 hours per week); - self-study in computer class (doing home assignments using Excel and Econometric views, work with economic data, appliances in Internet); - self-study with literature. 
 
Assessment and grade determination 
 
- test (90 minutes) - home assignements (at least one) - written exam (150 minutes) 
 2
Grade determination: 
 
First term grade is to 100% determined by the exam in December. The overall grade for the course is a weighted average of the first term grade (40%), home assignment grade average (10%) and the final exam (April) grade (50%). Exam (finals in December and April) grades can’t be less than satisfactory for a student to get a positive grade for the whole course. 
 
Main reading 
 
1. Patton, A. (2007). Quantitative Finance, UoL Study Guide. (AP) 2. Christoffersen, P.F. Elements of Financial Risk Management. (Academic Press, London, 2003).(PC) 3. Diebold, F.X. Elements of Forecasting. (Thomson South-Western, Canada, 2006) fourth edition. (FD) 4. Wilmott, P. Paul Wilmott on Quantitative Finance (selected chapters). 2nd ed. Wiley,       2006.  5. McNeil, A. J. et al, Quantitative Risk Management. Princeton University Press, 2005.  
 
 
Additional reading 
 
1. Enders W. Applied Econometric Time Series. 2nd ed., John Wiley & Sons, Inc., 2004 (WE) 2. Ruey S. Tsay (2002). Analysis of Financial Time Series. 3. Brooks (2002). Introductory econometrics for finance, Cambridge University Press. 4. Franke/ Haerdle/ Hafner (2004). Statistics of Financial Markets, Springer. 5. Hamilton, J. (1994), Time Series Analysis, Princeton University Press, Princeton 
 
Course outline 
 
1. Basic time series concepts Many problems in quantitative finance involve the study of financial data. Such data most often comes in the form of ‘time series’, which is a sequence of random variables that are ordered through time. Before moving on to financial applications, we must first cover some fundamental topics in time series analysis, such as autocorrelation, white noise processes and ARMA processes. This topic is the most theoretical one in the course, and it may not appear too related to finance, but it lays the foundations for the (more interesting) topics we will cover later. 
 
WE, Chapter 1-2; AP, Ch. 2; FD, Ch. 7-8 
 
2. Modelling asset return volatility: introduction Risk plays a central role in financial decision making, and it is thus no surprise that a great deal of effort has been devoted to the study of the volatility of asset returns. This effort has paid large dividends: volatility modelling and forecasting methods have been shown to be very useful in many economic applications. In this topic we will cover some of the most widely-used models for modelling volatility, discuss the estimation of these models, and methods of testing for volatility predictability. 
 
WE, Chapter 3; AP, Ch. 4; CP, Ch. 2 
 
3. Modelling asset return volatility: extensions In this chapter we discuss extensions of the basic ARCH/GARCH class of models, both univariate and multivariate. Univariate extensions have been proposed to capture more detailed 
 3
features of asset return volatility, such as the so-called .leverage effect.. Multivariate extensions of the GARCH model are used to assist with financial decisions that involve more than one risky asset, such as portfolio decisions or risk management. 
 
AP, Ch. 5, CP Ch. 2-3; WE, Chapter 3 
 
4. Evaluating forecasts of risks and returns There are often many competing statistical models available for use in the forecasting of a particular financial variable. There are also many commercially available forecasts, issued by brokers or mutual funds. How do we determine whether the forecast is good or not? How do we determine which model or forecaster is best? These two questions relate to forecast evaluation and comparison. A third question that arises is whether we can take a collection of forecasts and combine them somehow to get an even better forecast. We will cover methods for answering these questions in this topic. 
 
AP, Ch. 6; WE, Chapter 2, FD Ch. 12, CP 2, particularly 2.6 
 
 – Semester break –  
 
5. The efficient market hypothesis and market predictability  Much of modern quantitative finance relates to methods and models for predicting aspects of asset returns, and yet the classical theory of efficient markets may appear to suggest that asset returns should be completely unpredictable. In this topic we relate the concept of efficient markets, defined in various ways, to the evidence of predictability of financial variables and reconcile the empirical evidence for asset return predictability with the concept of an efficient market. 
 
WE, Chapter 3 
 
6. Risk management and Value-at-Risk: models  Measuring and managing the exposure to risk generated by a trading desk, a structured product, or a traditional portfolio is one of the most important and interesting parts of quantiative .nance. Modern risk management focuses heavily on a measure of risk known as “Value-at-Risk”, or VaR. This is partly due to some advantages of this measure over variance, and partly due to regulation (the Basel Accords are based on VaR as a measure of risk). In this topic we will introduce VaR formally and discuss some of the most common models for measuring VaR. 
 
WE, Chapter 5 
 
7. Risk management and Value-at-Risk: backtesting An important part of managing risk is testing how well your risk models are performing, a task known in the risk management literature as backtesting. Such tests can also be useful for indicating ways to improve risk models. This topic will cover some methods for backtesting VaR models. 
 
8. Modelling high frequency financial data Traditionally, empirical studies in  finance employed data at the daily and monthly frequencies. Many models and methods have been developed for the study of such data. Recently, high frequency (intra-day) has become available to researchers, and empirical market microstructure is now an established sub-field within  finance. Many of the methods developed for lower frequency data are applicable to high frequency data, but there are a few places where differences exist, and we will study two of these in this topic. How one treats the massive amounts of high frequency data available should depend on the problem the researcher wishes to 
 4
address. In many cases, the question can be addressed by aggregating the  tick  data up to a certain frequency and then analyze the sequence of aggregated returns. Doing so makes the data evenly spaced, and thus more similar to well-studied low frequency data. Many questions, however, are best addressed using tick data, meaning that we must  find ways of dealing with the irregularly-spaced observations. Another problem that arises in certain analyses of high frequency data is seasonality. Seasonality is a well-studied problem in macro- and micro-econometrics, but is not generally a concern for  financial econometricians. Intra-daily patterns (called ‘diurnality’ rather than ‘seasonality’ ) in certain measures are significant and must be dealt with. Three places where diurnality in high frequency returns has been found to be prominent are in the conditional variance, in bid-ask spreads and in trade durations.  

 

 
