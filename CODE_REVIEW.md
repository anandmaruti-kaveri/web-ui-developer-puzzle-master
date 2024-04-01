code review :
1. need to create one Base components and need to extend every components.
2.create one util file . if any common or re usable function we can add in util.
3.lazy loading missing book search
4.shared folder missing for common components (re use components)
5.book-search.component.ts file  component need to add ngdestroy and unsubscribe the api once it destroy
6.books-feature.module code split required (ex:angular mat module import need to be seperate file mat.module.ts)


improvements :
1.auto fill required for search (based on type autofill dropdown need to appier with lazyloading)
2.pagination or lazy scroll required to avoid one time render data(in home page)
3.reading list popup required once want to read button clicked 
4.conformation delete  popup required for my readlist.
 

