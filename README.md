# Angular-lessonsLearnt

## Error during importing custom module

"ERROR in : Unexpected module 'HeaderModule declared by the module 'AppModule'. Please add a @Pipe/@Directive/@Component annotation."

<strong> Reason </strong> 

Due to different angular version in the imported module and importing module
Module not added inside the import

## Cropped Vendor or inline or any bundle

<strong> Reason </strong> 

Due to Dynamic import

## Angular 5 to Angular 6

https://medium.com/@filipjerga/angular-5-to-angular-6-migration-guide-7ba4d2544411

## Capturing Query parameter and navigating by passing query parameter

 <pre>
 let queryParam = ActivatedRoute.snapshot.queryParams;
 Router.navigate([currentUrl], { queryParams: queryParam});
 </pre>
 
 interfaces only exist at compile-time. They don't exist at runtime.
 
 ## Images inside div
 
 need to add <code> display: block / vertical-align : buttom </code> to avoid line-height being applied to the img tag inside div

