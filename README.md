Can customized all in this source code
=====================================
  https://github.com/shwesinhtay111/AngularDashboardTemplate

----------------------------------------------------------------------

Or

Auto Create Angular Material Dashboard Layout
============================================
1.create angular new project, ng new projectName

2.cd projectName

3.ng add @angular/material [ if error, firstly install, npm i @angular/material @angular/cdk @angular/animations]

4.ng generate @angular/material:navigation nav

5.write in app.component.html, <app-nav></app-nav>

6.write in nav.component.html, content area,<router-outlet></router-outlet>

7.ng generate @angular/material:dashboard home

8.write in app-routing.module.ts, const routes: Routes = [
  { path: 'home', component: HomeComponent}
];

9.In browser test as, localhost:4200/home

------------------------------------------------------
![ScreenShot](https://www.google.com/url?sa=i&url=https%3A%2F%2Fkinsta.com%2Fblog%2Fjpg-vs-jpeg%2F&psig=AOvVaw02xZR_jKZtucVm7Ub33x18&ust=1605527436328000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCPjBjva9hO0CFQAAAAAdAAAAABAN)
