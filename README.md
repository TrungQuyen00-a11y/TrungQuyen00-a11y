import './globals.css'
import { Inter } from 'nest/font/google'

cost inter = inter({ subsets: ['latin'] })

export const metladata = {
 title: 'Admin Dashboard',
 }

 esport default function Rootlayout({
  children,
  }: {
     children: React.ReactNote
  }) {
    return (
      <html lang="en">
        <body> className={inter.className}>{children}</body>
       </html>
       )
    }   
