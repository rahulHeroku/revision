1. Is JSX mandatory for React? 
No
2. Is ES6 mandatory for React? 
No
3. {TitleComponent} vs {<TitleComponent/>} vs {<TitleComponent></TitleComponent>} in JSX 
A3: 
4. How can I write comments in JSX?
A4. // This is single line comment , /**
                                    *
                                    * This is multiline comment
                                    *
                                    */
5. What is <React.Fragment></React.Fragment> and <></> ?  
A5. It is a component which is export by 'React'.
 <React.Fragment> </React.Fragment>. Short hand to write it is <> </>. It acts like a virtual parent node.
6. What is Virtual DOM?
A6. It is an tree like Object which react maintains side by side with the actual DOM. One of the usecase is to make sure the reconcillatoin algo works efficiently and facliltate fast rendering of only those elements of the page which are changed due to user interaction.
7. What is Reconciliation in React? :
A7. Check notebook notes
8. What is React Fiber?
A3. https://sunnychopper.medium.com/what-is-react-fiber-and-how-it-helps-you-build-a-high-performing-react-applications-57bceb706ff3
9. Why we need keys in React? When do we need keys in React?
A9: Very important to make user that the process of reconcillatonc i.e., the diffing algo works error free. 
10. Can we use index as keys in React?
A10. If we will use index as component key then the reordering of list will change the key 
11. What is props in React? Ways to
12. What is a Config Driven UI ? When server send you a response in json according to which the higher level look and feel and data of the website is decided. For example: India has various regional festivals. Suppose if someone opens Swiggy on the day of Mahashivratri in Nothern part of India then he will see some Mahshivratri related offers while in Jammu and Kashmir the offers won't be festuve based at the same moment. 
